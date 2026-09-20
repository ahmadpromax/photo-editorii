# 📸 Photo Editorii | استودیو تخصصی ادیت و ریتاچ حرفه‌ای عکس

> **High-End Artisanal Photo Retouching & Cinematic Photomontage Studio**  
> لندینگ‌پیج رسمی، دوزبانه (فارسی / انگلیسی) و فوق‌سریع استودیو **فتو ادیتوری** مستقر روی GitHub Pages.

---

## 🌐 لینک‌های زنده پروژه (Live Deployments)

- 🇮🇷 **نسخه فارسی (پیش‌فرض):** [https://ahmadpromax.github.io/photo-editorii/](https://ahmadpromax.github.io/photo-editorii/)
- 🇬🇧 **نسخه انگلیسی (English Version):** [https://ahmadpromax.github.io/photo-editorii/en/](https://ahmadpromax.github.io/photo-editorii/en/)
- 🔗 **صفحه واسط بیو (Link-in-Bio Hub):** [https://ahmadpromax.github.io/photo-editorii/links/](https://ahmadpromax.github.io/photo-editorii/links/)

---

## 🎯 ویژگی‌های کلیدی و تمایز اجرایی

- **تفکیک فرکانسی دستی (Frequency Separation):** تفکیک لایه رنگ از بافت پوست جهت حذف لکه‌ها و جوش‌ها با حفظ ۱۰۰٪ منافذ و بافت طبیعی صورت (بدون بلورهای پلاستیکی هوش مصنوعی).
- **نورپردازی و عمق سینمایی (Dodge & Burn):** فرم‌دهی سه‌بعدی به چهره و تنظیم دقیق زاویه و دمای نور در پروژه‌های فتومونتاژ و فیس‌سواپ.
- **تعهد کاری و امحای امنیتی:** تحویل ۱۲ الی ۲۴ ساعته پروژه‌ها به همراه گارانتی اصلاح مجدد تا رضایت کامل، و حذف قطعی فایل‌ها از سیستم پس از ۷۲ ساعت.
- **اسلایدر قبل و بعد کاملاً Native:** پیاده‌سازی اسلایدر تعاملی مقایسه بدون وابستگی به کتابخانه‌های سنگین خارجی (Vanilla JS).

---

## ⚡ بهینه‌سازی‌های عملکردی و سئو (Technical Specs)

- **Mobile First & Core Web Vitals:**
  - صفر بودن شاخص مسدودی پردازنده (`TBT = 0ms`).
  - پایداری مطلق چیدمان و عدم پرش صفحه (`CLS = 0.00`).
  - بهینه‌سازی شاخص `LCP` از طریق تصاویر بهینه‌شده **WebP** و متاتگ اختصاصی `preload` در `<head>`.
- **سئو بین‌المللی و نشانه‌گذاری ساختاریافته (SEO & Schema):**
  - عناوین بهینه‌شده `<h1>` و متاتگ‌های تایتل و توضیحات استاندارد زیر ۶۰ و ۱۶۰ کاراکتر.
  - پیاده‌سازی کامل تگ‌های زبان بین‌المللی (`hreflang`: fa, en, x-default).
  - استفاده از نشانه‌گذاری استاندارد JSON-LD شامل انواع `ProfessionalService` و `FAQPage`.

---

## 📂 ساختار فایل‌های مخزن (Project Structure)

```text
photo-editorii/
├── index.html                  # نسخه اصلی و رسمی به زبان فارسی (RTL)
├── en/
│   └── index.html              # نسخه بین‌المللی به زبان انگلیسی (LTR)
├── links/
│   └── index.html              # صفحه واسط سبک و مینیمال (Link-in-Bio)
├── images/
│   ├── photo-editori-logo.webp # لوگوی اصلی برند استودیو
│   ├── hero-before.webp        # تصویر خام اسلایدر بخش هیرو
│   ├── hero-after.webp         # تصویر ریتاچ‌شده اسلایدر بخش هیرو
│   ├── montage-before.webp     # نمونه‌کار فتومونتاژ (قبل)
│   ├── montage-after.webp      # نمونه‌کار فتومونتاژ (بعد)
│   ├── beauty-before.webp      # نمونه‌کار بیوتی ریتاچ (قبل)
│   ├── beauty-after.webp       # نمونه‌کار بیوتی ریتاچ (بعد)
│   ├── enhance-before.webp     # نمونه‌کار ارتقای کیفیت (قبل)
│   └── enhance-after.webp      # نمونه‌کار ارتقای کیفیت (بعد)
├── robots.txt                  # راهنمای خزنده‌های موتورهای جستجو
├── sitemap.xml                 # نقشه سایت ثبت‌شده در گوگل سرچ کنسول
├── llms.txt                    # مستندات بهینه‌سازی برای مدل‌های زبانی و هوش مصنوعی
└── README.md                   # مستندات فنی مخزن
