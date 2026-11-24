# داشبورد عملیات باربری | Waybill Operations Dashboard

نمونه‌کار تعاملی بر اساس ساختار یک داشبورد Power BI برای عملیات باربری. داده‌ها با فرمولی ثابت در خود صفحه تولید می‌شوند و صرفاً برای نمایش قابلیت‌های نمونه‌کار هستند.

![نمای گزارش عملکرد در Power BI](screenshots/01-overview.png)

[مشاهدهٔ دموی آنلاین](https://anaram.github.io/waybill-operations-dashboard/)

## اجرا

فایل `index.html` را در مرورگر باز کنید. برای انتشار با GitHub Pages، فایل‌ها را در ریشهٔ مخزن بگذارید و در **Settings → Pages** شاخهٔ اصلی و پوشهٔ Root را انتخاب کنید.

## امکانات

- فیلتر ماه و استان مبدأ با اثر هم‌زمان بر نمودارها، کارت‌ها و جدول
- تغییر شاخص نمودارها بین تعداد بارنامه و کمیسیون
- روند ماهانه، مقایسهٔ استان‌های مبدأ و جدول مسیرها
- چیدمان فارسی راست‌چین و واکنش‌گرا

دادهٔ نمایشی شامل ۹۶ ردیف تجمیعی، حاصل ۱۲ ماه و ۸ مسیر فرضی است. میانگین کمیسیون با تقسیم مجموع کمیسیون بر تعداد بارنامه در محدودهٔ فیلتر محاسبه می‌شود. تعداد مسیر فعال، تعداد مسیرهای متمایز در همان محدوده است.

## English

A standalone, right-to-left portfolio demo inspired by a freight operations report. It uses deterministic synthetic data for 12 months and 8 example routes. Open `index.html` directly or host it on GitHub Pages. The demo works offline and has no external dependencies.

## فایل Power BI و تصاویر نمونه‌کار

[Waybill-Portfolio-Synthetic.pbix](Waybill-Portfolio-Synthetic.pbix) نسخهٔ کامل هشت‌صفحه‌ای است. آن را در **Power BI Desktop for Report Server (May 2026)** باز کنید. نمونهٔ HTML این مخزن یک دموی مستقل است و dataset جداگانه دارد.

فایل PBIX با **۲۶۳٬۸۱۱ بارنامهٔ ساختگی** و بدون اتصال به پایگاه دادهٔ شرکت ذخیره شده است. در صفحه‌های «عملکرد کلی» و «تحلیل جغرافیایی»، آبان ۱۴۰۵ با مهر ۱۴۰۵ مقایسه می‌شود. داده‌های ساختگی در هر پنج بازهٔ عددی نقشه‌های تعداد بارنامه و کمیسیون پراکنده شده‌اند. استان‌های خارج از نمونه سفید هستند و حالت «بدون داده» را نشان می‌دهند. نشان و پس‌زمینهٔ نسخهٔ اصلی در PBIX و تصاویر آن دیده می‌شوند.

- [عملکرد کلی و مقایسهٔ ماهانه](screenshots/01-overview.png)
- [تحلیل جغرافیایی و مقایسهٔ ماهانه](screenshots/02-geography.png)
- [نقشهٔ تعداد بارنامه](screenshots/03-province-waybills.png)
- [نقشهٔ کمیسیون](screenshots/04-province-commission.png)

