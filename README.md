# Ali Janati | علی جنتی

پورتفولیوی شخصی علی جنتی — برنامه‌نویس فرانت‌اند، متخصص امنیت، هوش مصنوعی و بازی‌سازی.

🌐 **آدرس سایت:** [https://ali-janati.github.io](https://ali-janati.github.io)

---

## درباره پروژه

یک وب‌سایت استاتیک و سبک برای معرفی مهارت‌ها، ویژگی‌ها و مدارک. بدون فریم‌ورک و وابستگی خارجی — فقط HTML، CSS و کمی JavaScript.

## ویژگی‌ها

- طراحی RTL و فارسی
- واکنش‌گرا (موبایل، تبلت، دسکتاپ)
- انیمیشن لودینگ در صفحه اصلی
- SEO و meta tagهای Open Graph
- استایل یکپارچه در یک فایل CSS
- ناوبری ساده بین صفحات

## ساختار پروژه

```
Ali-Janati.github.io/
├── index.html      # صفحه اصلی
├── maharat.html    # مهارت‌ها
├── vigi.html       # ویژگی‌ها
├── madarek.html    # مدارک و گواهینامه‌ها
├── style.css       # استایل مشترک همه صفحات
├── Vazir-Bold.ttf  # فونت فارسی
├── img/            # تصاویر مدارک و favicon
└── LICENSE
```

## تکنولوژی‌ها

- HTML5
- CSS3 (CSS Variables, Flexbox, Grid, Media Queries)
- JavaScript (Vanilla)
- GitHub Pages

## اجرای محلی

1. ریپازیتوری را clone کنید:

```bash
git clone https://github.com/Ali-Janati/Ali-Janati.github.io.git
cd Ali-Janati.github.io
```

2. یکی از روش‌های زیر را برای مشاهده سایت استفاده کنید:

**با VS Code / Cursor:** افزونه Live Server را نصب کنید و روی `index.html` کلیک راست → Open with Live Server

**با Python:**

```bash
python -m http.server 8000
```

سپس در مرورگر باز کنید: `http://localhost:8000`

**مستقیم:** فایل `index.html` را در مرورگر باز کنید (برای تست ساده کافی است).

## ثبت سایت در گوگل و بینگ (SEO)

فایل‌های آماده‌ی سئو در پروژه:

- `robots.txt` — مجاز کردن کرال و معرفی sitemap
- `sitemap.xml` — فهرست هر ۵ صفحه سایت
- `google04f1a9a112437360.html` — فایل تأیید مالکیت Google Search Console (قبلاً کامیت شده)
- تگ‌های `canonical`، `robots`، `og:url` و JSON-LD در `<head>` همه صفحات

### ۱) ثبت در Google Search Console

1. وارد [search.google.com/search-console](https://search.google.com/search-console) شوید.
2. یک Property از نوع **URL prefix** با آدرس `https://ali-janati.github.io/` بسازید.
3. برای تأیید مالکیت، روش **HTML file** را انتخاب کنید — فایل `google04f1a9a112437360.html` از قبل در ریشه سایت هست؛ کافی است روی **Verify** بزنید (اگر فایل را تازه آپلود کرده‌اید، اول push کنید و چند دقیقه صبر کنید).
4. از منوی **Sitemaps** آدرس `sitemap.xml` را ثبت کنید.
5. برای ایندکس سریع‌تر، در بخش **URL Inspection** آدرس `https://ali-janati.github.io/` را وارد کنید و **Request Indexing** بزنید.

### ۲) ثبت در Bing Webmaster Tools

**راه سریع (پیشنهادی):**

1. وارد [bing.com/webmasters](https://www.bing.com/webmasters) شوید و با حساب مایکروسافت لاگین کنید.
2. هنگام افزودن سایت گزینه **Import from Google Search Console** را انتخاب کنید — سایت و sitemap به‌صورت خودکار منتقل می‌شوند.

**راه دستی:**

1. در Bing Webmaster Tools یک سایت با آدرس `https://ali-janati.github.io/` اضافه کنید.
2. روش تأیید **Meta tag** را انتخاب کنید و تگی شبیه زیر را در `<head>` فایل `index.html` قرار دهید:

```html
<meta name="msvalidate.01" content="کد-دریافتی-از-بینگ" />
```

3. فایل را push کنید و در Bing روی **Verify** بزنید.
4. در بخش **Sitemaps** آدرس `https://ali-janati.github.io/sitemap.xml` را ثبت کنید.

> نکته: Bing از فایل تأیید گوگل (`google...html`) استفاده نمی‌کند؛ مالکیت بینگ باید جداگانه با کد خودش تأیید شود.

### ۳) بررسی وضعیت ایندکس

- گوگل: در Search Console بخش **Pages** (پوشش ایندکس) + جستجوی `site:ali-janati.github.io` در گوگل
- بینگ: در Webmaster Tools بخش **Site Explorer** + جستجوی `site:ali-janati.github.io` در بینگ

## استقرار روی GitHub Pages

این ریپازیتوری از نوع `username.github.io` است؛ با push به branch `main`، GitHub Pages به‌صورت خودکار سایت را منتشر می‌کند.

```bash
git add .
git commit -m "your message"
git push origin main
```

چند دقیقه بعد سایت در [https://ali-janati.github.io](https://ali-janati.github.io) در دسترس است.

## مجوز

این پروژه تحت مجوز [Apache License 2.0](LICENSE) منتشر شده است.

---

**Ali Janati** — [GitHub](https://github.com/Ali-Janati)
