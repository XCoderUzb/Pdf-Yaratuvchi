# PDF Usta

Rasmlarni PDF faylga aylantiruvchi, GitHub Pages’da ishlaydigan statik web-sayt. Barcha fayllar brauzerda qayta ishlanadi va serverga yuborilmaydi.

## Ishlatish

1. `index.html` faylini brauzerda oching yoki GitHub Pages orqali joylashtiring.
2. Bir yoki bir nechta rasm tanlang (yoki sahifaga sudrab tashlang).
3. Kerakli PDF sozlamalarini tanlab, **PDF yaratish** tugmasini bosing.

## GitHub Pages’ga chiqarish

Repository’ning **Settings → Pages** bo‘limida **Build and deployment → Source** sifatida **GitHub Actions** ni tanlang. `main` branch’ga yuborilgan o‘zgarishlar avtomatik ravishda Pages’ga chiqariladi. Sayt `https://xcoderuzb.github.io/Pdf-Yaratuvchi/` manzilida ochiladi.

PDF yaratish uchun jsPDF kutubxonasi CDN’dan olinadi; shu sababli PDF generatsiyasida internet aloqasi kerak bo‘ladi.
