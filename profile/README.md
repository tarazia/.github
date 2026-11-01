<p align="center">
  <a href="https://tarazia.online"><img src="https://tarazia.online/icon-512.png" width="96" alt="Tarazia"></a>
</p>

<h1 align="center">ترازیا | Tarazia</h1>
<p align="center">نرم‌افزار حسابداری آنلاین با هوش مصنوعی برای کسب‌وکارهای ایرانی</p>
<p align="center">
  <a href="https://tarazia.online">وب‌سایت</a> ·
  <a href="https://tarazia.online/developers">مستندات API</a> ·
  <a href="https://tarazia.online/developers/mcp">اتصال هوش مصنوعی (MCP)</a> ·
  <a href="https://tarazia.online/tools/invoice-generator">فاکتورساز رایگان</a>
</p>

---

## ترازیا چیست؟
فروش و خرید، فاکتور و صورتحساب رسمی، انبار، چک، حقوق و دستمزد، تولید، صندوق فروشگاهی و ارسال به سامانه مودیان، در یک نرم‌افزار ابری. دستیار هوش مصنوعی از روی عکس فاکتور پیش‌نویس سند می‌سازد و به سؤال‌های مالی به زبان ساده جواب می‌دهد.

## برای برنامه‌نویس‌ها

### 🔌 REST API
اشخاص، کالاها با موجودی هر انبار، و فاکتورها را بخوانید و ثبت کنید. ثبت فاکتور با `external_ref` تکرارناپذیر است، پس تلاش دوباره بعد از قطعی شبکه امن است.

- احراز هویت: `Authorization: Bearer dk_…` (کلید از تنظیمات API در ترازیا)
- دسترسی جدا برای خواندن و ثبت، در حد مجوزهای نقش کاربر سازنده‌ی کلید
- مشخصات OpenAPI: `https://tarazia.online/api/v1/openapi`

📘 [مستندات کامل API](https://tarazia.online/developers)

### 🤖 MCP: هوش مصنوعی خودتان را به حسابداری وصل کنید
Claude، ChatGPT یا Cursor را به ترازیا وصل کنید و به زبان عادی گزارش بگیرید یا اطلاعات ثبت کنید.

```bash
claude mcp add --transport http tarazia https://tarazia.online/mcp \
  --header "Authorization: Bearer dk_xxxxxxxxxxxxxxxx"


📘 راهنمای اتصال و فهرست ابزارها
```
🛒 افزونه‌ی ووکامرس
همگام‌سازی سفارش‌ها، فاکتور و موجودی فروشگاه وردپرسی با ترازیا.

<p align="center">۱۴ روز رایگان امتحان کنید: <a href="https://tarazia.online">tarazia.online</a></p>


**قبل از گذاشتن این متن، دو چیز را تأیید کنید:**
1. آدرس سرور MCP را `https://tarazia.online/mcp` نوشتم، چون در کد صفحه‌ی MCP مسیر `/mcp` آمده است. یک بار در صفحه‌ی `/developers/mcp` روی سایت چک کنید که همین باشد.
2. بخش ووکامرس فقط وقتی بماند که افزونه را عمومی یا قابل دانلود کرده‌اید. اگر نه، حذفش کنید یا لینکش را بدهید تا اضافه کنم.

اگر بخواهید، ریپوی `tarazia/examples` را هم با نمونه‌کدهای واقعی از روی همین API می‌سازم.
