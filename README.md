# Bahor Moda — Zebo uchun sinov sayti

Oddiy statik sayt: katalog (index.html), 3 ta mahsulot (p1–p3.html) va "Rahmat" sahifasi (rahmat.html).
Haqiqiy to'lov yo'q — faqat Zebo kuzatuv kodini qo'lda o'rnatib sinash uchun.

## Joylash (Vercel)
1. GitHub'da yangi repo oching (masalan `bahor-moda`) va shu papkadagi hamma fayllarni yuklang.
2. Vercel → Add New → Project → shu repo'ni tanlang → Deploy (sozlamalar shart emas).
3. Manzil chiqadi, masalan `https://bahor-moda.vercel.app`.

## Zebo'ga ulash
1. Zebo admin → Brendlar → Yangi brend: sayt — yuqoridagi manzil, kuzatuv usuli — "Kuzatuv kodi", komissiya 10%.
2. Brend kabineti → Sozlamalar → Ulanish: kodni nusxalang.
3. **1-qism** (`<script src="https://zeboshop.uz/t.js?b=..." async></script>`) — 5 ta HTML faylning hammasida
   `ZEBO KUZATUV KODI (1-qism) SHU YERGA` degan joyga qo'ying.
4. **2-qism** (sotuv kodi) — faqat `rahmat.html` dagi `ZEBO SOTUV KODI (2-qism)` joyiga qo'ying va
   `'BUYURTMA_RAQAMI'` → `ORDER_ID`, `BUYURTMA_SUMMASI` → `ORDER_SUM` qilib almashtiring.
5. GitHub'ga qayta yuklang — Vercel o'zi yangilaydi.
