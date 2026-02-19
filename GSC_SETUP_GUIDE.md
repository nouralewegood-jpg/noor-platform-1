# دليل ربط Google Search Console

## خطوات ربط موقع noor-platform-v1 مع Google Search Console

### الخطوة 1: الوصول إلى Google Search Console
1. توجه إلى [Google Search Console](https://search.google.com/search-console)
2. قم بتسجيل الدخول باستخدام حسابك على Google

### الخطوة 2: إضافة الموقع
1. انقر على **"إضافة خاصية"** (Add Property)
2. اختر **"بادئة URL"** (URL prefix)
3. أدخل رابط الموقع: `https://noor-platform-v1.vercel.app/`
4. انقر على **"متابعة"** (Continue)

### الخطوة 3: التحقق من الملكية
اختر إحدى طرق التحقق التالية:

#### الطريقة 1: ملف HTML (الموصى به)
1. قم بتحميل ملف HTML الذي يوفره Google Search Console
2. ضع الملف في مجلد `public/` في المستودع
3. ارفع التغييرات إلى GitHub
4. انقر على **"التحقق"** (Verify)

#### الطريقة 2: Meta Tag
1. انسخ Meta Tag الذي يوفره Google
2. أضفه إلى ملف `index.html` في قسم `<head>`
3. ارفع التغييرات إلى GitHub
4. انقر على **"التحقق"** (Verify)

#### الطريقة 3: DNS
1. انسخ سجل DNS المطلوب
2. أضفه إلى إعدادات DNS لنطاقك (إذا كان لديك نطاق خاص)
3. انقر على **"التحقق"** (Verify)

### الخطوة 4: إرسال Sitemap
بعد التحقق من الملكية:
1. توجه إلى قسم **"Sitemaps"** (الخرائط)
2. انقر على **"إضافة/اختبار Sitemap"**
3. أدخل: `https://noor-platform-v1.vercel.app/sitemap.xml`
4. انقر على **"إرسال"** (Submit)

### الخطوة 5: مراقبة الأداء
- **تقرير الأداء**: يعرض عدد الانطباعات والنقرات والموضع
- **تقرير التغطية**: يعرض الصفحات المفهرسة والأخطاء
- **تقرير التحسينات**: يعرض مشاكل الجوال والعلامات البنيوية

## الملفات المضافة للـ SEO

### 1. robots.txt
- **المسار**: `/public/robots.txt`
- **الوظيفة**: توجيه عناكب البحث حول الصفحات المراد فهرستها

### 2. sitemap.xml
- **المسار**: `/public/sitemap.xml`
- **الوظيفة**: توفير قائمة بجميع صفحات الموقع لمحركات البحث

### 3. Meta Tags المحسّنة
- **Title**: عنوان الصفحة الموصى به (60 حرف)
- **Description**: وصف الصفحة (160 حرف)
- **Keywords**: الكلمات المفتاحية الرئيسية
- **Canonical URL**: تحديد الصفحة الأساسية
- **Open Graph Tags**: لتحسين مشاركة الصفحة على وسائل التواصل
- **Twitter Card**: لتحسين مظهر الصفحة على تويتر

## نصائح إضافية للـ SEO

1. **تحسين سرعة الموقع**
   - استخدم أدوات مثل Google PageSpeed Insights
   - قلل حجم الصور
   - استخدم CDN

2. **تحسين المحتوى**
   - استخدم الكلمات المفتاحية بشكل طبيعي
   - أضف عناوين وصور وصفية
   - اكتب محتوى فريد وقيّم

3. **بناء الروابط الخلفية**
   - اطلب من المواقع الموثوقة الربط إلى موقعك
   - شارك محتواك على وسائل التواصل الاجتماعي

4. **مراقبة الأداء**
   - تحقق من تقارير Google Search Console بانتظام
   - راقب ترتيب الكلمات المفتاحية
   - اتخذ إجراءات تصحيحية عند الحاجة

## الموارد المفيدة

- [Google Search Console Help](https://support.google.com/webmasters)
- [Google SEO Starter Guide](https://developers.google.com/search/docs/beginner/seo-starter-guide)
- [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly)
- [PageSpeed Insights](https://pagespeed.web.dev/)

---

**ملاحظة**: قد يستغرق ظهور موقعك في نتائج البحث عدة أسابيع بعد إرسال Sitemap.
