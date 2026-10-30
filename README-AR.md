# FreeLLM Hub — نسخة أندرويد

## الحصول على APK من GitHub (بدون تثبيت أي شي)
1. أنشئ مستودعاً جديداً في github.com.
2. ارفع كل محتويات هذا المجلد (مع `.github`) من متصفح الكمبيوتر.
3. تبويب **Actions** ← سيبدأ «Build Android APK» تلقائياً (5–10 دقائق). الـ workflow يسوي مشروع أندرويد لحاله.
4. من التشغيلة المكتملة، نزّل **FreeLLM-Hub-apk** من Artifacts، وثبّت `app-debug.apk` على جوالك.

## البناء على جهازك
تحتاج Node.js و Android Studio:
```
npm install
npx cap add android
npx cap sync android
npx cap open android      # ثم Build ← Build APK
```

## الاستخدام
- القائمة ☰ ← «المزودون والمفاتيح» ← الصق مفتاح API ← حفظ.
- بدون مفتاح: Kilo Code و LLM7.io و OVHcloud.
- «جلب كل الموديلات» يضيف كل موديلات المزود.
- زر ＋ ← المقارنة وتعليمات النظام والحرارة.

## ملاحظات
- المفاتيح تُحفظ على الجوال فقط.
- داخل التطبيق الرد يوصل كامل دفعة وحدة (بدون بث) لتجاوز قيود CORS.
