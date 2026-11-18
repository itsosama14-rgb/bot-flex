# Bot Flex

واجهة عربية لمساعد ذكي تعمل مباشرة من مستندات Google Sheets عبر Google Apps Script.

## النشر

احتفظ بملف `index.html` في الجذر، ولا تستخدم مسارًا فرعيًا للواجهة.

لـ Vercel:
- Framework Preset: **Other**
- Root Directory: `./`
- Build Command: فارغ
- Output Directory: فارغ

بعد النشر، ضع رابط Web App الخاص بـ Apps Script في المتغير `SCRIPT_URL` داخل `index.html`.
