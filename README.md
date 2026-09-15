<div align="center">

<img src="./public/avatar.jpg" alt="Amir_Dig" width="140" height="140" />

# 🤖 Amir_Dig

### دستیار هوش مصنوعی فارسی‌زبان — رفیق، رک، دقیق

یه برنامه‌ی چت دسکتاپ که فقط و فقط فارسی حرف می‌زنه، خودمونی جواب می‌ده و با امنیت کامل روی ویندوز اجرا می‌شه.

<br>

[![Download](https://img.shields.io/badge/📥_دانلود-آخرین_نسخه-00e599?style=for-the-badge)](https://github.com/amirdig/amir-dig/releases/latest)
[![Version](https://img.shields.io/badge/version-1.0.0-00b8ff?style=for-the-badge)](https://github.com/amirdig/amir-dig/releases)
[![Platform](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/amirdig/amir-dig/releases)

<br>

![Persian](https://img.shields.io/badge/زبان-فارسی_روان-00e599?style=flat-square)
![AI](https://img.shields.io/badge/هوش_مصنوعی-Hugging_Face-FFD21E?style=flat-square)
![Secure](https://img.shields.io/badge/امنیت-رمزنگاری_توکن-2dd4a7?style=flat-square)

</div>

---

## 🎯 Amir_Dig چیه؟

**Amir_Dig** یه دستیار هوش مصنوعی فارسی‌زبانه که روی ویندوز نصب می‌شه و باهاش می‌تونی مثل یه رفیق حرف بزنی.

برخلاف دستیارهای دیگه که وسط فارسی، چینی یا عربی قاطی می‌کنن، Amir_Dig:

- 🗣️ **فقط فارسی حرف می‌زنه** — تمیز و روان
- 🤝 **خودمونی و رفیقانه جواب می‌ده** — نه خشک و اداری
- 🔒 **توکن شما رو رمزنگاری می‌کنه** — امن و مطمئن
- ⚡ **روی دسکتاپ ویندوز** با یه کلیک باز می‌شه

---

## ✨ ویژگی‌ها

| 💬 چت هوشمند | 🔐 امنیت |
|---|---|
| ✅ پاسخ‌های فارسی روان | ✅ رمزنگاری توکن با Windows |
| ✅ لحن رفیقانه و صمیمی | ✅ بدون ارسال داده به سرور اضافه |
| ✅ پشتیبانی از Markdown و کد | ✅ Rate Limiting روی درخواست‌ها |
| ✅ تغییر مدل به دلخواه | ✅ Content Security Policy |

| 💾 حافظه | 🎨 رابط کاربری |
|---|---|
| ✅ ذخیره‌ی خودکار چت‌ها | ✅ تم تاریک و روشن |
| ✅ جستجو توی تاریخچه | ✅ فونت فارسی Sahel |
| ✅ Pin و Rename گفتگوها | ✅ کاملاً RTL |
| ✅ Export/Import به JSON | ✅ ریسپانسیو |

---

## 📸 تصاویر

<div align="center">

| رابط اصلی چت | تنظیمات |
|:---:|:---:|
| ![Main](./docs/screenshots/main.png) | ![Settings](./docs/screenshots/settings.png) |

| تم روشن | صفحه‌ی ورود توکن |
|:---:|:---:|
| ![Light](./docs/screenshots/light.png) | ![Token](./docs/screenshots/token.png) |

</div>

---

## 📥 دانلود و نصب

### مرحله ۱: دانلود

برو به صفحه‌ی [**Releases**](https://github.com/amirdig/amir-dig/releases/latest) و فایل `Amir_Dig Setup 1.0.0.exe` رو دانلود کن.

> 💾 **حجم:** حدود ۹۰ مگابایت

### مرحله ۲: نصب

1. روی فایل `Amir_Dig Setup 1.0.0.exe` دابل‌کلیک کن
2. اگه ویندوز هشدار داد، روی **More info → Run anyway** بزن
3. مسیر نصب رو انتخاب کن (یا پیش‌فرض بذار)
4. **Install** رو بزن
5. منتظر بمون تا نصب تموم بشه

### مرحله ۳: اجرا

آیکون **Amir_Dig** رو روی دسکتاپ یا Start Menu پیدا کن و بازش کن. 🎉

---

## 🔑 گرفتن توکن Hugging Face

برای اینکه Amir_Dig بتونه جواب بده، به **توکن رایگان Hugging Face** نیاز داری. این کار ۲ دقیقه طول می‌کشه:

### مراحل

1. اگه حساب نداری، برو به [huggingface.co/join](https://huggingface.co/join) و ثبت‌نام کن (رایگانه)

2. برو به این لینک:

   👉 [**huggingface.co/settings/tokens/new**](https://huggingface.co/settings/tokens/new?ownUserPermissions=inference.serverless.write&tokenType=fineGrained)

3. تنظیمات توکن:
   - **Token type:** `Fine-grained`
   - **Name:** یه اسم دلخواه (مثلاً `Amir_Dig`)
   - تیک ✅ **Make calls to Inference Providers** رو بزن

4. روی **Create token** کلیک کن

5. توکن رو کپی کن (شروع می‌شه با `hf_...`)

6. توی Amir_Dig پیستش کن و **ادامه** رو بزن

> 🔒 **امنیت:** Amir_Dig توکن رو رمزنگاری‌شده روی سیستم خودت ذخیره می‌کنه. به هیچ سروری نمی‌فرسته (به‌جز Hugging Face که خودت داری باهاش حرف می‌زنی).

---

## 🚀 شروع استفاده

### اولین اجرا

```
1. Amir_Dig رو باز کن
       ↓
2. توکن HF رو پیست کن
       ↓
3. ادامه رو بزن
       ↓
4. شروع به چت کن! 🎉
```

### نمونه پیام

```
سلام داداش، حالت چطوره؟
```

```
یه کد پایتون بنویس که یه لیست رو مرتب کنه
```

```
قیمت بیت‌کوین الان چنده؟
```

---

## 🌐 اگه توی ایران هستی

برای اینکه Amir_Dig به Hugging Face وصل بشه، باید **VPN یا پروکسی** روشن باشه.

### پیشنهاد: Hiddify / v2rayN / Clash

**قبل از باز کردن Amir_Dig**، یکی از اینا رو روشن کن:

| برنامه | پورت پیش‌فرض |
|--------|-------------|
| **Hiddify** | `12334` |
| **v2rayN** | `10809` |
| **Clash** | `7890` |

Amir_Dig **خودکار** پروکسی رو تشخیص می‌ده. فقط کافیه برنامه‌ی VPN باز باشه. ✅

> 💡 **بهترین حالت:** حالت **TUN Mode** یا **System Proxy** رو توی VPN روشن کن.

---

## ❓ سوالات متداول

<details>
<summary><b>🔴 برنامه باز نمی‌شه</b></summary>

<br>

**راه‌حل:**
1. ویندوزت باید ۱۰ یا ۱۱ (۶۴ بیت) باشه
2. اگه آنتی‌ویروس بلاکش کرده، بهش اجازه بده
3. یه بار ری‌استارت کن و دوباره امتحان کن

</details>

<details>
<summary><b>🔴 خطای «توکن نامعتبر»</b></summary>

<br>

**راه‌حل:**
1. مطمئن شو توکن رو کامل کپی کردی (شروع می‌شه با `hf_`)
2. مطمئن شو تیک **Make calls to Inference Providers** رو زدی
3. یه توکن جدید بساز

</details>

<details>
<summary><b>🔴 خطای «شبکه برقرار نشد»</b></summary>

<br>

**راه‌حل:**
1. VPN / پروکسی رو روشن کن
2. Amir_Dig رو ببند و دوباره باز کن
3. اگه بازم نشد، پروکسی رو با یه برنامه‌ی دیگه امتحان کن

</details>

<details>
<summary><b>🔴 برنامه انگلیسی یا چینی جواب می‌ده</b></summary>

<br>

**راه‌حل:**
1. تنظیمات → AI / Model → مدل رو عوض کن به **Llama 3.3 70B**
2. Temperature رو کمتر کن (مثلاً `0.2`)
3. از System Prompt این متن رو اضافه کن: «فقط و فقط فارسی جواب بده»

</details>

<details>
<summary><b>🔴 چطور توکنم رو پاک کنم؟</b></summary>

<br>

**راه‌حل:**
1. تنظیمات → Token / Account
2. دکمه‌ی **حذف توکن** رو بزن
3. توکن جدید وارد کن

</details>

<details>
<summary><b>🔴 می‌تونم ازش توی موبایل استفاده کنم؟</b></summary>

<br>

فعلاً نه. Amir_Dig فقط برای **ویندوز** ساخته شده. نسخه‌ی موبایل توی برنامه‌های آینده هست.

</details>

---

## 🎁 مدل‌های پشتیبانی‌شده

Amir_Dig از این مدل‌ها پشتیبانی می‌کنه (توی تنظیمات قابل انتخاب):

| مدل | حجم | کیفیت فارسی | سرعت |
|-----|-----|-------------|------|
| **Qwen2.5 72B** | 72B | 🏆 عالی | متوسط |
| **Llama 3.3 70B** | 70B | 🏆 عالی | متوسط |
| **Aya Expanse 32B** | 32B | ⭐ خوب | سریع |
| **Qwen2.5 32B** | 32B | ⭐ خوب | سریع |

> 💡 **پیشنهاد:** اگه نتت ضعیفه، **Qwen2.5 32B** رو انتخاب کن. اگه نت خوبی داری و کیفیت برات مهم‌تره، **Qwen2.5 72B**.

---

## 🆘 پشتیبانی

اگه مشکلی داشتی:

1. اول [سوالات متداول](#-سوالات-متداول) رو ببین
2. اگه جوابت نبود، [**یه Issue باز کن**](https://github.com/amirdig/amir-dig/issues/new)
3. توی Issue اینا رو بنویس:
   - مشکل چیه
   - دقیقاً چه کاری کردی
   - چه خطایی گرفتی (اسکرین‌شات یا متن خطا)

---

## 📋 تغییرات نسخه‌ها

### 🆕 v1.0.0 — اولین انتشار

- ✅ چت با مدل‌های فارسی Hugging Face
- ✅ رابط کاربری زیبا با تم تاریک/روشن
- ✅ ذخیره‌ی رمزنگاری‌شده‌ی توکن
- ✅ تشخیص خودکار پروکسی
- ✅ حافظه‌ی کاربر
- ✅ Export/Import چت‌ها
- ✅ پشتیبانی کامل RTL و فونت Sahel

---

## 📜 مجوز

این پروژه تحت مجوز **MIT** منتشر شده. استفاده، تغییر، و توزیع آزاده.

```
MIT License · Copyright (c) 2026 Amir_Dig
```

---

## 🙏 تشکر از

- [Hugging Face](https://huggingface.co/) برای API رایگان
- [Electron](https://www.electronjs.org/) برای فریمورک دسکتاپ
- [Sahel Font](https://github.com/rastikerdar/sahel-font) برای فونت زیبای فارسی
- همه‌ی مدل‌سازهایی که فارسی رو زنده نگه داشتن 💚

---

<div align="center">

<br>

### ⭐ اگه از Amir_Dig راضی بودی، یه ستاره بده! ⭐

ساخته شده با ❤️ برای مردم فارسی‌زبان

<br>

[📥 دانلود آخرین نسخه](https://github.com/amirdig/amir-dig/releases/latest) · [🐛 گزارش باگ](https://github.com/amirdig/amir-dig/issues/new)

<br>

</div>
