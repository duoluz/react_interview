# PROJECT_REQUIREMENTS

Assalomu alaykum!

Frontent dasturchisi uchun test loyihasini taqdim etish uchun keeling React va TypeScript yordamida oddiy veb-ilovani yarataylik.
Bizning ilovamiz oddiy BLOG tizimi funksiyalaridan tashkil topkan.

## Texnologiyalar:
* Node.js 17 +
* React
* TypeScript
* Redux
* Redux Toolkit
* RTK Query (Веб сервиларга мурожат қилиш ва маълумотларни кешлаш мақсадида ишлатиш мумкин)
* Tailwind(Бунинг ўрнига Bootstrap ишлатишингиз хам мумкин)
* json-server(Mock api сервер сифатида ишлатиш мумкин)

### Loyiha vazifalari:

**Maydonlar bilan blogni (Blog) ifodalash uchun ob'ekt yarating:**
* id (unikal identifikator)
* sarlavha (blog nomi)
* mavzu (mavzu nomi, olhida jadvalga olib chiqish mu’mkin)
* matn (blog mazmuni HTML formatta)
* yaratilgan sana (blog jadvalga yozilgan sana)
* oqilishlar soni (blog ochib oqilishlar soni)
* tekshirilgan (moderator tomonidan tekshirilganligi true/false)

**Maydonlar bilan blog uchun izohni (Comment) ifodalash uchun ob'ekt yarating:**
* id (unikal identifikator)
* blog_id(blog bilan bog’lanish kaliti)
* izoh (izoh matn korinishida uzunligi 400 dan oshmasligi shart)
* yaratilgan sana (izoh jadvalga yozilgan sana)
* foydaliligi (izoh foydaliligi soni)
* foydasizligi (izoh foydasizligi soni)
* tekshirilgan (moderator tomonidan tekshirilganligi true/false)

**HTTP so'rovlarini boshqarish uchun service ishlab chiqing:**
* Barcha bloglar ro'yxatini ko'rsatish (jumladan, tekshirilgan va tekshirilmagan).
* Yangi blog qo'shish.
* Blogni toliq ko’rish
* Blogni tekshirilgan deb belgilash.
* Blogni o'chirish.
* Blog uchun izohlar ro’yxatini ko’rsatish.
* Blog uchun izoh kiritish .
* Tasdiqlanmagan izohlar ro’yxatini ko’rsatish.
* Izohni tasdiqlangan deb belgilash.
* Izohni o’chirish.

3. React va TypeScript yordamida bloglar roʻyxatini, blog toliq ko’rinishini, tasdiqlanmagan izohlar ro’yxatini va yangi blog qoʻshish uchun formani yarating.

4. Ilova uchun unit testlarni yozing (barcha holatlarni qamrab olish shart emas, lekin hech bo'lmaganda asosiy funksional qismlar uchun tezt yozing).

5. Majburiy emas: bloglar va tasdiqlanmagan izohlar roʻyxatlarida sahifada pagination amalga oshiring.

Qoshimcha ma’lumolar:

1. Ilova kodlarini https://github.com/duoluz/react_interview projectga o’zingizning ismfamilya (damir_asamatdinov) ko’rinishidagi branchga yuklang.

### Qoshimcha imkoniyatlarni qoshish haqida
Bu test loyihasining asosiy versiyasi bo'lib, siz o'z tajribalaringizga asoslanib uni foydalanuvchi autentifikatsiyasi, 
blogni tahrirlash va shu kabi qo'shimcha funktsiyalar bilan kengaytirishingiz mumkin. Tekshirishni osonlashtirish uchun kodingizni sharhlashni unutmang.

Agar sizda biron bir savol paydo bo'lsa bizaga murajat qilishingiz mumkin

### Test loyihangizga omad tilaymiz! 


