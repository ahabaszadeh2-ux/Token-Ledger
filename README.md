Add files via upload
cd token-ledger-app
npm install
npm run dist

فایل خروجی داخل پوشهٔ release/ قرار می‌گیرد. جزئیات کامل (از جمله محدودیت مهم: ساخت .dmg فقط روی macOS ممکن است) در فایل README.md داخل زیپ نوشته شده.


ذخیره‌سازی داده‌ها در فایل واقعی روی دیسک (نه فقط localStorage)
امکان انتخاب پوشهٔ ذخیره‌سازی از داخل برنامه
سورد قابل تغییر در index.html

const AUTH_USERNAME = 'admin';
const AUTH_PASSWORD = 'change-me-1234';
