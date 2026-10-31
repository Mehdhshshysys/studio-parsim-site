# استودیو پارسیم | وب‌سایت رسمی

وب‌سایت فارسی و راست‌چین استودیو پارسیم با طراحی واکنش‌گرا، صحنهٔ مفهومی خودروی اسپرت، افکت‌های سه‌بعدی CSS، شبکهٔ نئونی، کارت‌های تعاملی و پویانمایی‌های نارنجی/آبی.

## اجرا
فایل `index.html` را مستقیماً در مرورگر باز کنید؛ برای این نسخه نیازی به نصب وابستگی یا اجرای فرایند build نیست.

## انتشار با GitHub Pages
این سایت از ریشهٔ شاخهٔ `main` منتشر می‌شود. در تنظیمات مخزن، بخش **Settings → Pages** باید منبع انتشار روی `Deploy from a branch`، شاخهٔ `main` و پوشهٔ `/ (root)` باشد.

## جلوه‌های بصری
- صحنهٔ خودروی مفهومی SVG با عمق و شناوری سه‌بعدی
- شهر نئونی، حلقه‌های نورانی و کف شبکه‌ای
- واکنش سه‌بعدی به حرکت نشانگر روی دسکتاپ
- رعایت تنظیمات کاهش حرکت سیستم برای دسترس‌پذیری

## پروژه‌ها
- **Nuvora OS**: [صفحهٔ برنامه در مایکت](https://myket.ir/app/app.nuvora.phone)
- **سلطان جاده**: کارت معرفی آماده است؛ لینک فروشگاه پس از تأیید انتشار عمومی اضافه شود.

## هویت و دارایی‌ها
- لوگوی استودیو (ستارهٔ ختایی + «پ») به‌صورت SVG داخل صفحه‌ها و در `assets/logo.svg` قرار دارد؛ برای جایگزینی با فایل نهایی کافی است همین فایل‌ها و نمادِ `parsim-logo` عوض شوند.
- اسپلش کوتاه استودیو فقط یک‌بار در هر نشست نمایش داده می‌شود و با کاهش حرکت غیرفعال است.
- تصاویر گالری سلطان جاده تصویرسازی مفهومی‌اند؛ اسکرین‌شات واقعی بازی هنوز اضافه نشده است.
- Nuvora OS در مایکت منتشر شده است.

## یادداشت
فونت Vazirmatn از Google Fonts بارگذاری می‌شود؛ در صورت نبود دسترسی شبکه، فونت جایگزین سیستم استفاده خواهد شد.


## Interactive 3D hero
The homepage hero includes a procedural Three.js sports-car scene with metallic materials, lighting, orbit rings and particles. Inspired by techniques seen in [Formwork Heliodon](https://github.com/shellcat-com/formwork-heliodon) and [Three.js examples](https://threejs.org/examples/). The existing page illustration remains as a fallback if WebGL or the CDN is unavailable.
