تشغيل محلي:
1) npm install
2) حدد DATABASE_URL في متغيرات البيئة (أو ملف .env) يشاور على قاعدة Postgres محلية أو على Railway
3) npm run migrate   (مرة واحدة فقط، بيعمل الجداول ويضيف رقم تجريبي)
4) npm start

الرفع على Railway:
1) ارفع الفولدر ده على GitHub
2) في Railway: New -> GitHub Repository -> اختار المستودع
3) أضف PostgreSQL من نفس المشروع (Railway بيربط DATABASE_URL أوتوماتيك)
4) بعد أول نشر، شغّل مرة واحدة: npm run migrate (من تبويب الأوامر/Shell في Railway)
