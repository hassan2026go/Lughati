# لُغتي Studio — مشروع Android (نسخة 1.2)

هذا مشروع Android Studio أولي يغلّف واجهة لُغتي 1.2 داخل WebView محلي.
ملف الواجهة ومحرك اللغة مضمّنان داخل `app/src/main/assets/index.html`.

## المتطلبات
- Android Studio حديث.
- JDK 17 أو أحدث.
- Android SDK Platform 35.
- Android Gradle Plugin 8.7.3، وسيجلب Gradle التبعيات عند أول مزامنة.

## البناء
1. افتح المجلد `Lughati-Android-1.2` في Android Studio.
2. نفّذ Gradle Sync.
3. اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
4. ملف APK التجريبي يظهر عادة في `app/build/outputs/apk/debug/app-debug.apk`.

## ما يتضمنه الغلاف
- تطبيق مستقل باسم لُغتي.
- تشغيل الواجهة محلياً دون الحاجة إلى خادم أو صلاحية إنترنت.
- JavaScript وDOM Storage لحفظ تفضيلات المظهر محلياً.
- فتح الملفات عبر منتقي مستندات Android.

## حدود النسخة الحالية
- هذه حزمة مصدر Android قابلة للفتح في Android Studio، وليست APK مبنياً.
- لم يتوفر Android SDK أو Gradle في بيئة إعداد هذه الحزمة، لذلك لم يُنفّذ بناء APK هنا.
- اختيار مجلد كامل من منتقي Android لم يُربط بعد؛ استيراد ملفات JSON والملفات المفردة مدعوم من خلال منتقي الملفات.
- لا تتضمن هذه النسخة مزامنة سحابية أو مساعداً ذكياً أو صلاحيات شبكة.
- نواة لُغتي وواجهة HTML الأصلية محفوظتان كما هما داخل الأصول؛ لا يتم تحويل اللغة إلى Java/Kotlin في هذه المرحلة.

التوقيع داخل واجهة لُغتي محفوظ: `yasser Alhussen/daraa - syria`
