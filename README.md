# Axranka Bot

<div align="center">
  <img src="https://sdmntprnorthcentralus.oaiusercontent.com/files/00000000-5640-622f-9699-328691773283/raw?se=2025-04-17T20%3A38%3A08Z&sp=r&sv=2024-08-04&sr=b&scid=067fa9f3-cef3-50eb-8a1b-169257a4dc5c&skoid=54ae6e2b-352e-4235-bc96-afa2512cc978&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-04-17T07%3A24%3A04Z&ske=2025-04-18T07%3A24%3A04Z&sks=b&skv=2024-08-04&sig=9VRxhTcW518xWcimriwcXbuaSoqpRBrGcMFl4zyua24%3D" alt="Axranka Bot Logo">
  <h3>Guruhlarni boshqarish va himoya qilish uchun kuchli Telegram bot</h3>
</div>

## 📋 Umumiy ma'lumot

Axranka Bot - bu guruhlarni boshqarish, spam va reklamalardan himoya qilish, ko'ngilochar o'yinlar o'ynash va boshqa ko'plab foydali funksiyalarni taqdim etuvchi kuchli Telegram bot. Bot guruh adminlariga keng qamrovli boshqaruv imkoniyatlarini beradi va barcha a'zolar uchun foydali xizmatlarni taqdim etadi.

**Bot manzili:** [https://t.me/oxranka_bot](https://t.me/oxranka_bot)

## ✨ Asosiy imkoniyatlar

### 👮‍♂️ Guruh boshqaruvi
- Guruh sozlamalarini to'liq boshqarish
- Foydalanuvchilarni cheklash (ban, mute, kick)
- Xabarlarni moderatsiya qilish va yuqoriga qistirish
- Majburiy a'zolikni tekshirish
- Guruh qoidalarini boshqarish
- Yangi a'zolarga salomlashish xabarlari

### 🛡️ Himoya funksiyalari
- Spam va reklamalarni filtrlash
- Taqiqlangan so'zlarni boshqarish
- Havolalar va forward xabarlarni nazorat qilish
- Media (stikerlar, GIF) cheklovlari
- Avtomatik ogohlantirish tizimi

### 🎮 Ko'ngilochar funksiyalar
- So'z o'yinlari va reytinglar
- So'rovnomalar yaratish
- Avtomatik javoblar
- Eslatmalar va bildirishnomalar

### 🔧 Foydali funksiyalar
- Ob-havo ma'lumotlari
- Valyuta kurslari
- Yangiliklar
- Veb-sayt skrinlari
- Vaqt va sana ma'lumotlari

### 📊 Admin panel
- Foydalanuvchilar va guruhlarga xabarlar yuborish
- Batafsil statistika
- Avtomatik javoblarni boshqarish
- Turli xil media bilan postlar yaratish
- Taqiqlash tizimini boshqarish

## 🚀 O'rnatish

### Talab qilinadigan dasturlar
- Python 3.8+
- pip (Python paketlarini boshqarish tizimi)
- [@BotFather](https://t.me/BotFather) dan olingan Telegram Bot Tokeni

### O'rnatish bosqichlari
1. Repozitoriyani klonlash:
\`\`\`bash
git clone https://github.com/roobotmee/axranka-bot.git
cd axranka-bot
\`\`\`

2. Kerakli kutubxonalarni o'rnatish:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

3. `.env` faylini yaratish va sozlash:
\`\`\`
BOT_TOKEN=sizning_bot_tokeningiz
ADMIN_ID=sizning_telegram_id_raqamingiz
\`\`\`

4. Ma'lumotlar bazasini ishga tushirish:
\`\`\`bash
python init_db.py
\`\`\`

5. Botni ishga tushirish:
\`\`\`bash
python bot.py
\`\`\`

## 📚 Buyruqlar ro'yxati

### Asosiy buyruqlar
| Buyruq | Tavsifi |
|--------|---------|
| `/start` | 🚀 Botni ishga tushirish |
| `/help` | 📖 Yordam va buyruqlar ro'yxati |
| `/id` | 🆔 Foydalanuvchi ID sini ko'rish |
| `/gid` | 🆔 Guruh ID sini ko'rish |
| `/soat` | ⏰ Hozirgi vaqtni ko'rsatish |
| `/sana` | 📅 Bugungi sanani ko'rsatish |
| `/link` | 🔗 Guruh havolasini olish |
| `/user` | 🧾 Foydalanuvchi haqida ma'lumot |
| `/stat` | 📊 Bot statistikasini ko'rish |

### Admin buyruqlari
| Buyruq | Tavsifi |
|--------|---------|
| `/sozlama` | ⚙️ Guruh sozlamalarini boshqarish |
| `/addmem` | ➕ A'zo qo'shishni majburiy qilish |
| `/deladmin` | 👋 Foydalanuvchini adminlikdan chiqarish |
| `/fulladmin` | 🛡 To'liq admin huquqini berish |
| `/pin` | 📌 Xabarni yuqoriga qistirish |
| `/ro` | 🤐 Foydalanuvchini "faqat o'qish" rejimiga o'tkazish (2 soatga) |
| `/unro` | 💬 "Faqat o'qish" rejimini olib tashlash |
| `/kick` | 👞 Foydalanuvchini guruhdan chiqarish |
| `/ban` | 🚫 Foydalanuvchini guruhdan bloklash |
| `/unban` | ✅ Foydalanuvchini blokdan chiqarish |
| `/warn` | ⚠️ Foydalanuvchiga ogohlantirish berish |
| `/unwarn` | 🧹 Ogohlantirishlarni olib tashlash |
| `/silent` | 🔇 Doimiy yozishdan cheklash |
| `/unsilent` | 🔊 Doimiy cheklovni olib tashlash |
| `/admin` | 👤 Foydalanuvchini admin qilish |
| `/qoidalar` | 📜 Guruh qoidalarini ko'rish |
| `/setqoidalar` | 📝 Guruh qoidalarini o'rnatish |
| `/setwelcome` | 👋 Yangi a'zoga xush kelibsiz xabari |
| `/require` | 📌 Majburiy a'zolikni yoqish |
| `/delrequire` | ❌ Majburiy a'zolikni o'chirish |
| `/disableaddmem` | 📴 Majburiy a'zolikni vaqtinchalik o'chirish |
| `/unrestrict_all` | 🔓 Barcha foydalanuvchilardagi cheklovni olib tashlash |
| `/adminlist` | 📋 Guruh adminlari ro'yxatini ko'rish |

### Ko'ngilochar buyruqlar
| Buyruq | Tavsifi |
|--------|---------|
| `/poll` | 📊 So'rovnoma yaratish |
| `/wordgame` | 🎲 So'z o'yinini boshlash |
| `/guess` | 🔤 So'z o'yinida harf taxmin qilish |
| `/stopgame` | 🛑 So'z o'yinini to'xtatish |
| `/eslatma` | ⏳ Eslatma yaratish |

### Foydali buyruqlar
| Buyruq | Tavsifi |
|--------|---------|
| `/screen` | 🖼 Web-sayt skrinini olish |
| `/ob_havo` | 🌦 Ob-havo ma'lumotlarini ko'rish |
| `/kurs` | 💱 Valyuta kurslarini ko'rish |
| `/yangilik` | 📰 Yangiliklar olish |
| `/inline` | 🧩 Inline buyruqlarni ko'rish |
| `/til` | 🌍 Bot tilini o'zgartirish |

### Super admin buyruqlari
| Buyruq | Tavsifi |
|--------|---------|
| `/panel` | 🔸 Admin panelni ochish |
| `/send` | 📨 Barcha foydalanuvchilarga xabar yuborish |
| `/sozlar` | 📝 Avtomatik javoblar ro'yxatini ko'rish |
| `/delsoz` | 🗑 Avtomatik javobni o'chirish |

## 📊 Admin panel imkoniyatlari

Admin panel bot egasi va super adminlar uchun qo'shimcha boshqaruv imkoniyatlarini taqdim etadi:

### 📨 Xabar yuborish bo'limi
- **👤 Foydalanuvchilarga xabar yuborish**: Barcha ro'yxatdan o'tgan foydalanuvchilarga xabar yuborish
- **👥 Guruhlarga xabar yuborish**: Bot qo'shilgan barcha guruhlarga xabar yuborish
- **📢 Barchaga xabar yuborish**: Barcha foydalanuvchilar va guruhlarga bir vaqtning o'zida xabar yuborish
- **HTML formatida xabarlar**: Xabarlarni qalin, kursiv va havola bilan formatlash imkoniyati
- **Yuborish statistikasi**: Yuborilgan xabarlar va xatoliklar haqida batafsil ma'lumot

### 📊 Statistika bo'limi
- **Foydalanuvchilar soni**: Botdan foydalanuvchilar umumiy soni
- **Guruhlar soni**: Bot qo'shilgan guruhlar soni
- **Avtomatik javoblar soni**: Tizimda mavjud avtomatik javoblar soni
- **Faol foydalanuvchilar**: Oxirgi vaqtda faol bo'lgan foydalanuvchilar soni
- **Yangi qo'shilganlar**: Bugun qo'shilgan yangi foydalanuvchilar soni

### 🔤 So'z qo'shish bo'limi
- **Trigger so'zlar qo'shish**: Guruhda ishlatilganda avtomatik javob qaytariladigan so'zlarni qo'shish
- **Ko'p javobli so'zlar**: Bir so'zga bir nechta javob variantlarini qo'shish
- **Tasodifiy javob**: Bir nechta javobdan tasodifiy birini tanlash
- **Javoblarni boshqarish**: Mavjud so'z va javoblarni ko'rish va o'chirish
- **Guruhga bog'lash**: So'zlarni ma'lum bir guruhga yoki barcha guruhlarga bog'lash

### 📝 Post yaratish bo'limi
- **Oddiy post**: Matnli post yaratish va yuborish
- **Rasmli post**: Rasm va izoh bilan post yaratish
- **Videoli post**: Video va izoh bilan post yaratish
- **So'rovnoma**: Ko'p variantli so'rovnomalar yaratish
- **Tugmali postlar**: Postlarga havola tugmalarini qo'shish
- **HTML formatlash**: Postlarda HTML formatidan foydalanish
- **Post ko'rinishini oldindan ko'rish**: Yuborishdan oldin postni ko'rish va tekshirish

### 🚫 Ban bo'limi
- **Taqiqlangan so'zlar qo'shish**: Guruhlarda taqiqlanadigan so'zlarni qo'shish
- **Taqiqlangan so'zlar ro'yxati**: Mavjud taqiqlangan so'zlarni ko'rish
- **So'zlarni o'chirish**: Taqiqlangan so'zlarni ro'yxatdan olib tashlash
- **Avtomatik jazo**: Taqiqlangan so'z ishlatilganda avtomatik jazo berish sozlamalari

## ⚙️ Guruh sozlamalari

Bot quyidagi guruh sozlamalarini taqdim etadi:

- **Reklama va havolalar**: Reklama va havolalarni filtrlash
- **Stikerlar va GIF**: Stikerlar va GIF larni cheklash
- **Forward xabarlar**: Forward qilingan xabarlarni nazorat qilish
- **Yangi a'zolar**: Yangi a'zolarga salomlashish xabarlari
- **Majburiy a'zolik**: Majburiy a'zolik sozlamalari
- **Avtomatik javoblar**: Guruhga xos avtomatik javoblar
- **Taqiqlangan so'zlar**: Guruhda taqiqlangan so'zlar ro'yxati

## 📊 Ma'lumotlar bazasi tuzilishi

Bot SQLite ma'lumotlar bazasidan foydalanadi va quyidagi asosiy jadvallarni o'z ichiga oladi:

- `users` - Foydalanuvchilar ma'lumotlari
- `groups` - Guruhlar ma'lumotlari
- `settings` - Guruh sozlamalari
- `auto_replies` - Avtomatik javoblar
- `banned_words` - Taqiqlangan so'zlar
- `warnings` - Foydalanuvchi ogohlantirishlari
- `silent_users` - Doimiy cheklangan foydalanuvchilar

## 🧩 Loyiha tuzilishi

\`\`\`
axranka-bot/
├── bot.py                  # Asosiy bot fayli
├── config.py               # Konfiguratsiya sozlamalari
├── database.py             # Ma'lumotlar bazasi funksiyalari
├── states.py               # FSM holatlari
├── admin_panel.py          # Admin panel funksiyalari
├── admin_broadcast.py      # Xabar yuborish funksiyalari
├── help_command.py         # Yordam buyrug'i
├── url_validation.py       # URL tekshirish funksiyalari
├── broadcast_functions.py  # Xabar yuborish utilitlari
├── post_handlers.py        # Post yaratish hendlerlari
├── post_creation.py        # Post yaratish funksiyalari
├── main_handlers.py        # Asosiy buyruq hendlerlari
└── requirements.txt        # Loyiha bog'liqliklari
\`\`\`

## 🔧 Texnik ma'lumotlar

- Python va Aiogram 3.x frameworkida yaratilgan
- Ma'lumotlarni saqlash uchun SQLite dan foydalaniladi
- Holatlarni boshqarish uchun FSM (Finite State Machine) qo'llaniladi
- Inline tugmalar va klaviaturalar bilan interaktiv interfeys
- Xabarlarda HTML formatlashni qo'llab-quvvatlaydi

## 📞 Bog'lanish

**Dasturchi:**
- **Telegram:** [roobotmee](https://t.me/roobotmee)
- **Instagram:** [ismoiloff.uz](https://instagram.com/ismoiloff.uz)
- **GitHub:** [roobotmee](https://github.com/roobotmee)

## 📄 Litsenziya

Ushbu loyiha MIT litsenziyasi ostida tarqatiladi - batafsil ma'lumot uchun [LICENSE](LICENSE) faylini ko'ring.
\`\`\`

Men README.md faylini Uzbek tilida yangiladim va dasturchi ma'lumotlarini qo'shdim. Bot manzili ham qo'shildi: https://t.me/oxranka_bot

Logo uchun vaqtinchalik placeholder qo'yildi, chunki yuborilgan URL manzili ishlamayapti. Logo tayyor bo'lganda, uni placeholder o'rniga qo'yishingiz mumkin.

<Actions>
  <Action name="Logo qo'shish" description="Botning logotipini README fayliga qo'shish" />
  <Action name="Qo'shimcha funksiyalar qo'shish" description="README fayliga qo'shimcha funksiyalar haqida ma'lumot qo'shish" />
  <Action name="O'rnatish qo'llanmasini kengaytirish" description="Botni o'rnatish bo'yicha batafsil qo'llanma qo'shish" />
  <Action name="Skrinshot qo'shish" description="Bot interfeysining skrinshot rasmlarini qo'shish" />
  <Action name="Tez-tez so'raladigan savollar qo'shish" description="FAQ bo'limini qo'shish" />
</Actions>

\`\`\`

