# V-Taper Haftalık Planı

Kişisel hipertrofi + rekompozisyon (kas koruma/hafif büyüme + yağ azaltma) antrenman programı. Push/Pull/Legs mantığıyla kurgulanmış, haftalık sabit ritimde ilerleyen, tek dosyalık statik bir web sayfası.

**Canlı sayfa:** https://adanedhelwrites.github.io/adanedhel-working-program/

## Program mantığı

- **Şaşmaz kural:** 2 gün idman → 1 gün OFF.
- **Haftalık ritim (sabit):** Pazartesi/Salı/Perşembe/Cuma idman · Çarşamba/Cumartesi tam dinlenme · Pazar esnek/yedek gün.
- **Split rotasyonu:** İtiş A (göğüs öncelikli) → Çekiş A (genişlik) → Bacak (kısa) → İtiş B (omuz) → Çekiş B (kalınlık), sırayla döner; haftanın günü sabit kalır, hangi split'in o güne denk geldiği rotasyona göre ilerler.
- **Esnek/yedek gün (Pazar):** İstersen tam dinlenme, istersen o hafta kaçırılan bir antrenmanın telafisi.
- **Kaçırma kuralı:** Bir gün kaçırılırsa sıra atlanmaz, art arda 2 idman gününü aşmayacak şekilde bir sonraki uygun güne kaydırılır ya da o hafta için bırakılır.
- **Form notları:** Bench açısı, squat derinliği, RDL kalça menteşesi, OHP hizası, plank hizalaması gibi kritik noktalarda küçük SVG diyagram + kısa açıklama.
- **Serbest ağırlık alternatifleri:** Salon yoğunluğunda (özellikle cable istasyonları) kullanılamayan hareketler için her satırda dumbbell/bodyweight alternatifi var; cable-bağımlı hareketlerin çoğu doğrudan serbest ağırlık ana harekete çevrildi.

## Dosyalar

| Dosya | Amaç |
|---|---|
| `index.html` | GitHub Pages'in yayınladığı canlı sayfa (kök dizin) |
| `v-taper-haftalik-plan.html` | Aynı içeriğin yerel çalışma kopyası |
| `favicon.svg` | Sekme ikonu (hero'daki V-taper işaretinin küçültülmüş hali) |

`index.html` ile `v-taper-haftalik-plan.html` aynı içeriği taşır — biri deploy edilen kopya, diğeri yerelde açıp bakmak için. Bir değişiklik yapıldığında ikisi birlikte güncellenir.

## Güncelleme akışı

1. İlgili `.html` dosyasında hareket/gün/form notu değişikliği yapılır.
2. `git add`, `git commit`, `git push` — ekstra build adımı yok, statik dosya doğrudan servis ediliyor.
3. GitHub Pages ~30-60 saniye içinde otomatik yeniden build alır, canlı link güncellenir.

## Notlar

- Programın gerçek kişisel verisi (kilo, boy, sağlık geçmişi vb.) bu depoda tutulmuyor; sayfa sadece antrenman planını içeriyor.
- Sayfa framework kullanmıyor — saf HTML/CSS/JS, tek dosya, harici bağımlılık yalnızca Google Fonts (Oswald + Inter).
