# راهنمای کامپایل و خروجی گرفتن اندروید (APK) و موبایل — Dummynation Ultra v2.0

این پکیج به طور کامل برای تبدیل به اپلیکیشن موبایل (Android APK / iOS / PWA) آماده شده است:

## روش ۱: کامپایل با Capacitor (پیشنهادی و مدرن برای Android Studio)
1. پوشه پروژه را اکسترکت کنید.
2. دستور `npm install` را اجرا کنید.
3. دستور `npx cap add android` و سپس `npx cap sync` را بزنید.
4. با دستور `npx cap open android` پروژه در Android Studio باز می‌شود و از منوی `Build > Build Bundle(s) / APK(s) > Build APK` فایل نصبی `.apk` تولید می‌گردد.

## روش ۲: کامپایل سریع با Apache Cordova
1. دستور `cordova platform add android` را اجرا کنید.
2. دستور `cordova build android --release` را بزنید تا فایل APK ساخته شود.

## روش ۳: تبدیل یک‌کلیکی با Website2APK یا WebIntoApp
کافی است پوشه `www` (یا فایل `www/index.html`) را به نرم‌افزار Website2APK Builder بدهید تا در چند ثانیه فایل `.apk` آماده نصب روی گوشی تولید شود.
