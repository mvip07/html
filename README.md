## 🔤 **HTML nima?**

**HTML** — bu web sahifani tuzadigan til. To‘liq nomi **HyperText Markup Language**.

## ❓ **HTML nima uchun kerak?**

U yordamida matnlar, rasmlar, tugmalar, ro'yxatlar, videolar va boshqa elementlar sahifada qanday ko‘rinishda bo‘lishi belgilanadi.

---

## 🏷️ **<DOCTYPE html> nima?**

Brauzerga bu **HTML5** ekanini aytadi. Har doim faylning eng yuqorisida yoziladi.

---

## 🧱 **HTML tarkibi:**

### 📌 **html tag**

Barcha HTML kodlar shu tag orasida yoziladi. (`<html> ... </html>`)

### 🧠 **head qismi**

Sayt haqida **meta ma'lumotlar** yoziladi: `<title>`, `<meta>`, `<link>` va h.k.

### 👁 **body qismi**

Foydalanuvchiga ko‘rinadigan **asosiy kontent** shu yerda: matn, rasm, video va boshqalar.

---

## 🧠 **head ichidagi muhim taglar:**

### ⚙️ **meta**

Sayt haqida maxsus info beradi (charset, description, viewport, SEO uchun kerak).

### 📛 **title**

Brauzer oynasida chiqadigan sayt nomi.

### 🔗 **<link>**

Tashqi fayllarga bog‘laydi, masalan CSS fayliga (`rel="stylesheet"`).

---

## 📑 **Matn taglari:**

* **Heading taglar (h1 - h6)** — Sarlavhalar. `h1` eng kattasi, `h6` eng kichigi.
* **p** — Oddiy paragraf (matn qatori).
* **hr** — Gorizontal chiziq chizadi.
* **br** — Yangi qatordan boshlash uchun (break).
* **sub** — Pastga tushgan matn (masalan, H₂O).
* **sup** — Yuqoriga ko‘tarilgan matn (masalan, a²).
* **mark** — Matnni sariq rangda ajratadi.
* **u** — Matn ostiga chiziq chizadi.
* **ins** — Qo‘shilgan matn (ostiga chiziq).
* **del** — O‘chirilgan matn (ustiga chiziq).
* **strong** — Muhim matn (semantik jihatdan muhim, **qalin**).
* **b** — Qalin matn (oddiy qalin yozuv).
* **i** — Qiyshaygan yozuv.
* **em** — E’tiborli (semantik) qiyshaygan yozuv.
* **address** — Manzil yozish uchun.
* **abbr** — Qisqartmani belgilaydi (`title` atribut bilan tushuntirish qo‘shiladi).
* **time** — Vaqt ko‘rsatadi (`datetime` atribut bilan).

---

## 💬 **Izoh:**

* **<!-- -->** — HTMLdagi izoh (foydalanuvchiga ko‘rinmaydi).

---

## 📋 **Ro‘yxatlar:**

### ✅ **ul** — Belgili ro‘yxat (bullet list)

### 🔢 **ol** — Raqamli ro‘yxat (ordered list)

### 🔠 **li** — Ro‘yxat elementi

### 📘 **dl** — Tushuntirma ro‘yxat (definition list)

* **dt** — Tushunchaning nomi
* **dd** — Tushunchaning izohi

### 🎯 **Listda type atribut nima qiladi?**

Ro‘yxat belgilarini o‘zgartiradi:

* **ul**: `disc`, `circle`, `square`
* **ol**: `1`, `A`, `a`, `I`, `i`

### 🏁 **start atribut**

`ol` da raqamni qaysidan boshlashni belgilaydi (`start="5"` bo‘lsa, 5 dan boshlaydi).

---

## 🔗 **a tag**

Havola (link) yaratadi. Boshqa sahifaga yoki faylga olib boradi.

### 📎 **href**

Qayerga olib borishini ko‘rsatadi.

### 📥 **download**

Havolani bosganda faylni yuklab beradi.

### 🪟 **target**

Havola qanday ochilishini belgilaydi:

* `_blank` — Yangi oynada
* `_self` — Shu oynada (default)
* `_top`, `_parent` — Kam ishlatiladi

### ❓ **href="#"**

Havola hech qayerga olib bormaydi, lekin JavaScript bilan ishlatish mumkin.

---

## 🖼 **Multimedia:**

### **img** — Rasm qo‘yadi

* `src` — Rasm manzili
* `width`, `height` — O‘lchami

### **video** — Video qo‘yadi

* `src` — Video fayl
* `controls` — Play/pause tugmalari
* `autoplay`, `loop`, `muted`, `preload` — Qo‘shimcha xatti-harakatlar

### **audio** — Audio qo‘yadi

* Parametrlari video bilan bir xil

---

## 🧩 **Semantik taglar nima va nima uchun kerak?**

Bu taglar sahifani **ma’noli** tuzishda yordam beradi:

| Tag     | Nima uchun kerak              | Qayerda ishlatiladi          |
| ------- | ----------------------------- | ---------------------------- |
| header  | Sahifa yoki bo‘lim sarlavhasi | Eng tepada                   |
| main    | Sahifaning asosiy mazmuni     | Kontentlar orasida           |
| section | Bo‘lim                        | Biror mavzuni ajratish uchun |
| footer  | Oxirgi qism                   | Sayt yoki maqola oxiri       |
| nav     | Navigatsiya (menu)            | Asosiy menyu                 |
| article | Mustaqil maqola               | Yangiliklar, bloglar         |
| aside   | Yon panel, reklama            | Kontentdan tashqari          |

---

## 🔎 **details, summary**

* **details** — Yashirilgan kontentni ochadi/yopadi
* **summary** — Ko‘rinadigan sarlavha

---

## 🔣 **div & span**

* **div** — Blok elementi. Qismlarga bo‘lish uchun.
* **span** — Inline elementi. Matn ichida ushlab olish uchun.

---

## 🧮 **Jadval (table):**

| Tag                                       | Vazifasi                                          |
| ----------------------------------------- | ------------------------------------------------- |
| table                                     | Jadval yaratadi                                   |
| thead                                     | Jadval sarlavhasi                                 |
| tr                                        | Qator (row)                                       |
| th                                        | Sarlavha ustuni (qalin)                           |
| tbody                                     | Asosiy qism                                       |
| td                                        | Jadvaldagi katak                                  |
| tfoot                                     | Jadval oxiri                                      |
| rowspan                                   | Katakni bir nechta qatorga cho‘zadi               |
| colspan                                   | Katakni bir nechta ustunga cho‘zadi               |
| border, cellpadding, align, width, height | Jadvalga chiziq, joy, kenglik va balandlik beradi |

---

## 📝 **Form nima uchun kerak?**

Foydalanuvchidan **ma’lumot olish** (login, ro'yxatdan o'tish, izoh, qidiruv va h.k.).

### 📍 Form elementlari:

* **label** — Input uchun nom
* **placeholder** — Ichida ko‘rinadigan soxta matn
* **value** — Inputdagi qiymat
* **disabled** — Foydalanuvchi o‘zgartira olmaydi
* **readonly** — Faqat o‘qish mumkin, lekin jo‘natiladi

---

### 🧾 **input typelari (hammasi):**

| type                       | Vazifasi                          |
| -------------------------- | --------------------------------- |
| text                       | Matn yozish                       |
| password                   | Parol, yulduzcha bilan ko‘rinadi  |
| email                      | Email kiritish                    |
| number                     | Raqam                             |
| checkbox                   | Belgilash                         |
| radio                      | Variantlar (birini tanlash)       |
| date, time, datetime-local | Sana/vaqt                         |
| file                       | Fayl tanlash                      |
| color                      | Rang tanlash                      |
| range                      | Sürgüli qiymat                    |
| hidden                     | Ko‘rinmas qiymat                  |
| search                     | Qidiruv                           |
| tel                        | Telefon raqami                    |
| url                        | Link kiritish                     |
| submit                     | Yuborish                          |
| reset                      | Tozalash                          |
| button                     | Oddiy tugma (hech narsa qilmaydi) |

---

### 🔽 **select**

Variantlar ro‘yxati.

* **multiple** — Ko‘p tanlashga ruxsat
* **size** — Ko‘rinadigan variantlar soni

### ➕ **optgroup**

Select ichidagi guruh.

### 🔍 **datalist**

Input uchun variantlar ro‘yxati (autosuggest).

### 🗒 **textarea**

Ko‘p qatorli matn (izohlar uchun).

* `rows`, `cols` bilan o‘lchami belgilanadi.

### 🔘 **button**

Tugma yaratadi. `type="submit"` yoki `type="button"` bo‘lishi mumkin.
