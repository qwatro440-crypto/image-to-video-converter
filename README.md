# تحويل الصور إلى فيديو

Image To Video Converter تطبيق Android متكامل لتحويل سلسلة من الصور إلى ملف فيديو واحد بسهولة.

## المميزات ✨
- ✅ اختيار عدة صور من الهاتف
- ✅ معاينة الصورة الأولى
- ✅ تحويل الصور لفيديو بجودة عالية
- ✅ واجهة سهلة باللغة العربية
- ✅ دعم جميع إصدارات Android 24+
- ✅ استخدام FFmpeg للمعالجة الاحترافية

## المتطلبات
- Android Studio 2022 أو أحدث
- Android SDK 34
- Kotlin 1.8+
- Git

## التثبيت والتشغيل
### 1. استنساخ المشروع
```bash
git clone https://github.com/qwatro440-crypto/image-to-video-converter.git
cd image-to-video-converter
```
### 2. فتح المشروع
- افتح Android Studio
- اختر File → Open
- اختر المجلد المستنسخ
### 3. تثبيت المكتبات
- Android Studio سيقوم تلقائياً بتحميل المكتبات
- إذا لم يحدث، اذهب إلى Build → Rebuild Project
### 4. تشغيل التطبيق
- اختر جهاز أو محاكي
- اضغط Run (الزر الأخضر) أو Shift + F10

## طريقة الاستخدام
1. **افتح التطبيق** على هاتفك
2. **اضغط زر "اختيار الصور"**
3. **اختر صورتين أو أكثر** من معرض هاتفك
4. **اضغط زر "إنشاء الفيديو"**
5. **انتظر المعالجة** (قد تستغرق دقيقة حسب عدد الصور)
6. **الفيديو محفوظ** في: `Documents/Videos/`

## الملفات الرئيسية
```
app/src/main/java/com/example/imagetovideo/
├── MainActivity.kt          # الشاشة الرئيسية
└── VideoConverter.kt        # معالج تحويل الصور

app/src/main/res/
├── layout/
│   └── activity_main.xml    # تصميم الواجهة
└── ...
```

## المكتبات المستخدمة
- **Kotlin**: لغة البرمجة الحديثة
- **Coroutines**: للمعالجة غير المتزامنة
- **FFmpeg**: لمعالجة الفيديو
- **AndroidX**: مكتبات Android الحديثة

## الأذونات المطلوبة
- `READ_EXTERNAL_STORAGE`: قراءة الصور من الهاتف
- `WRITE_EXTERNAL_STORAGE`: حفظ الفيديو
- `READ_MEDIA_IMAGES`: قراءة الوسائط (Android 13+)
- `INTERNET`: للاتصال

## حل المشاكل
### المشكلة: "لا يمكن اختيار الصور"
**الحل**: اذهب إلى إعدادات > التطبيق > الأذونات وأعطِ إذن الوصول للصور
### المشكلة: "الفيديو لم ينشئ"
**الحل**: تأكد من أنك اخترت صورتين على الأقل وأن الهاتف لديه مساحة فارغة كافية

## المبرمج
Developed by: **qwatro440-crypto**

## الترخيص
MIT License - استخدم المشروع بحرية في مشاريعك الخاصة

## المساهمة
النقد والاقتراحات مرحباً بها! يمكنك:
1. Fork المشروع
2. إنشاء فرع جديد (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'Add amazing feature'`)
4. Push للفرع (`git push origin feature/amazing-feature`)
5. فتح Pull Request

---
**استمتع باستخدام التطبيق! 🎬📱**