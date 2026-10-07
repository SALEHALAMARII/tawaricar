# Deploy Checklist — GitHub Pages + Hostinger DNS

1. ارفع محتويات مجلد V3 إلى **جذر** مستودع GitHub.
2. GitHub → Settings → Pages → Deploy from branch → الفرع الرئيسي → `/ (root)`.
3. تأكد أن ملف `CNAME` في الجذر يحتوي `tawaricar.com`.
4. من Hostinger DNS طبّق سجلات الدومين المخصصة التي تعرضها/توصي بها وثائق GitHub Pages الحالية، وأضف `www` بالطريقة التي يوصي بها GitHub إن رغبت في تحويله إلى الدومين الأساسي.
5. بعد نجاح التحقق في GitHub Pages فعّل **Enforce HTTPS**.
6. افتح: `/`, `/dammam/`, `/khobar/`, `/qatif/`, و3–4 Money Pages وتأكد من 200 ومن الصور والأزرار.
7. أنشئ Google Search Console **Domain Property** للدومين، ثم أرسل `https://tawaricar.com/sitemap.xml`.
8. اختبر Mobile Lighthouse/PageSpeed بعد أن يصبح الدومين Live. أصلح أي LCP/CLS/INP يظهر من الشبكة الحقيقية قبل حملات الإعلانات أو بناء الروابط.
9. أضف GA4 Measurement ID عند توفره؛ `main.js` يرسل `click_call` و`click_whatsapp` تلقائيًا إذا كان `gtag` موجودًا.
10. لا تنشئ ثلاثة Google Business Profiles للمدن. استخدم ملفًا حقيقيًا ومتوافقًا مع قواعد Service Area Business إذا كانت المتطلبات مستوفاة.
