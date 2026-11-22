# Iran Network Monitor · پایش شبکه ایران

**English** · [فارسی](#فارسی)

A Telegram bot, [@inmapp](https://t.me/inmapp), that watches the health of Iranian networks and hosting providers from outside Iran, measures real bandwidth with iperf3, and publishes clear visual reports in Persian and English.

[🤖 Open the bot](https://t.me/inmapp) · [📢 Channel](https://t.me/IranNetworkMonitoring) · [🤝 Sponsors and hostings: @aqabolbol](https://t.me/aqabolbol)

## Why

Before buying a VPS in Iran you want to know how it really performs: speed at midday and at evening peak, stability, and how often it goes down. Iran Network Monitor measures this every day and publishes it openly.

## Features

| | |
|---|---|
| 🧭 **BGP maps** | Route maps and intelligence for operators, ISPs, infrastructure, data centres and hostings. Check any IP. |
| 📡 **Network monitoring** | Continuous checks from servers abroad to Iranian servers. A single failed sample is never reported as an outage; confirmed disruptions are shown separately from probe errors. |
| 🚀 **Speed tests (iperf3)** | Download, upload, jitter and packet loss between servers abroad and Iranian hostings, every day at **12:00, 20:00 and 23:00** (Tehran time). |
| 🔥 **Peak hours** | 20:00 and 23:00 are highlighted with the change compared to midday, so you can see how much bandwidth drops at peak usage. |
| 📊 **Weekly report** | Hostings ranked by average download, upload, stability and disruptions, with a 7-day status grid and a conclusion. |
| 🌐 **Persian and English** | Menus and reports in both languages. |

## How the speed test works

1. A client on a server abroad connects to the iperf3 server on the Iranian host.
2. Download is measured with 8 parallel streams for 30 seconds; upload uses the reverse mode.
3. A short UDP test measures jitter and packet loss.
4. Results are published as a card with one 7-day chart per test time.

## Use it

1. Open [@inmapp](https://t.me/inmapp) and press **Start**.
2. Choose **Speed test**, **BGP**, **Hostings** or **Providers** from the menu.
3. Press **Weekly report** for the latest ranking.

## Sponsors and hosting providers

Want to sponsor the bot, or have your hosting added to the reports? Message **[@aqabolbol](https://t.me/aqabolbol)** on Telegram.

⭐ If you find it useful, please star this repository!

> The bot's source code is private and proprietary. All rights reserved.

---

<a id="فارسی"></a>

# فارسی

ربات [@inmapp](https://t.me/inmapp) وضعیت شبکه‌ها و هاستینگ‌های ایران را از بیرون کشور زیر نظر دارد، پهنای باند واقعی را با iperf3 اندازه می‌گیرد و گزارش‌های تصویری روشن به فارسی و انگلیسی منتشر می‌کند.

[🤖 ورود به ربات](https://t.me/inmapp) · [📢 کانال](https://t.me/IranNetworkMonitoring) · [🤝 اسپانسر و هاستینگ: @aqabolbol](https://t.me/aqabolbol)

## چرا؟

قبل از خرید سرور مجازی در ایران باید بدانید کیفیت واقعی آن چقدر است: سرعت در ظهر و در ساعت‌های پیک شب، پایداری و تعداد قطعی‌ها. پایش شبکه ایران این را هر روز اندازه می‌گیرد و شفاف منتشر می‌کند.

## امکانات

| | |
|---|---|
| 🧭 **نقشهٔ BGP** | نقشه و اطلاعات مسیر برای اپراتورها، ISPها، زیرساخت، دیتاسنترها و هاستینگ‌ها. بررسی IP دلخواه. |
| 📡 **پایش شبکه** | بررسی مداوم از سرورهای خارج به سرورهای ایران. یک نمونهٔ ناموفق هرگز اختلال حساب نمی‌شود و اختلال تأییدشده از خطای پروب جدا نشان داده می‌شود. |
| 🚀 **تست سرعت (iperf3)** | دانلود، آپلود، جیتر و پکت‌لاس بین سرورهای خارج و هاستینگ‌های ایران، هر روز ساعت **۱۲، ۲۰ و ۲۳** به وقت تهران. |
| 🔥 **ساعات پیک** | ساعت ۲۰ و ۲۳ با تغییر نسبت به ظهر مشخص می‌شود تا ببینید پهنا در اوج مصرف چقدر افت می‌کند. |
| 📊 **گزارش هفتگی** | رتبه‌بندی هاستینگ‌ها بر اساس میانگین دانلود، آپلود، پایداری و اختلال، با جدول وضعیت ۷ روز و جمع‌بندی. |
| 🌐 **فارسی و انگلیسی** | منوها و گزارش‌ها به هر دو زبان. |

## تست سرعت چطور انجام می‌شود؟

۱. کلاینت روی سرور خارج به سرور iperf3 هاست ایرانی وصل می‌شود.
۲. دانلود با ۸ جریان موازی و ۳۰ ثانیه اندازه‌گیری می‌شود؛ آپلود با حالت معکوس.
۳. یک تست کوتاه UDP جیتر و پکت‌لاس را می‌سنجد.
۴. نتیجه به شکل کارتی با یک نمودار هفت‌روزه برای هر ساعت تست منتشر می‌شود.

## استفاده

۱. [@inmapp](https://t.me/inmapp) را باز کنید و **Start** را بزنید.
۲. از منو **تست سرعت**، **BGP**، **هاستینگ‌ها** یا **پروایدرها** را انتخاب کنید.
۳. برای آخرین رتبه‌بندی **گزارش هفتگی** را بزنید.

## اسپانسر و افزودن هاستینگ

اگر می‌خواهید اسپانسر ربات شوید یا هاستینگ شما به گزارش‌ها اضافه شود، در تلگرام به **[@aqabolbol](https://t.me/aqabolbol)** پیام بدهید.

⭐ اگر مفید بود، لطفاً به این مخزن استار بدهید!

> سورس ربات خصوصی و اختصاصی است. همهٔ حقوق محفوظ است.
