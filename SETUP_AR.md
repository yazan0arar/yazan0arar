# تركيب تصميم GitHub Terminal

هذا المشروع مجهز لحساب: `yazan0arar`

## الطريقة الأسهل

1. فك ضغط الحزمة.
2. افتح مستودع GitHub: `yazan0arar/yazan0arar`.
3. ارفع **كل محتويات المجلد** كما هي، وليس المجلد الخارجي نفسه.
4. تأكد أن الملفات التالية ظاهرة في الصفحة الرئيسية للمستودع:
   - `README.md`
   - `yazan-ascii.svg`
   - `info-card.svg`
   - `contrib-heatmap.svg`
   - `contribution-snake.svg`
   - مجلد `scripts`
   - مجلد `data`
   - مجلد `.github`

الصورة الأصلية وملف `source-prepped.png` غير مطلوبين على GitHub، ولا أنصح
برفعهما لأن ملف `yazan-ascii.svg` النهائي جاهز بالفعل.

## تشغيل التحديث اليومي

1. افتح تبويب **Actions**.
2. اختر **Refresh Profile Art**.
3. اضغط **Run workflow**.
4. بعد ظهور علامة النجاح الخضراء، ارجع إلى صفحة حسابك وحدّثها.

## إذا ظهر خطأ صلاحيات

افتح:

`Settings > Actions > General > Workflow permissions`

اختر **Read and write permissions** ثم اضغط **Save** وأعد تشغيل الـworkflow.

لا تحتاج إلى Personal Access Token ولا تضع أي كلمة مرور داخل الملفات.

## تعديل المعلومات لاحقًا

- معلومات البطاقة: `scripts/make_info_card.py`
- ألوان وحركة الصورة: `scripts/make_ascii_svg.py`
- ألوان وحركة المساهمات: `scripts/render_heatmap_svg.py`
- حركة الحية: `scripts/render_snake_svg.py`
- روابط التواصل: `README.md`

بعد تعديل بطاقة المعلومات شغّل:

`python scripts/make_info_card.py`

أما الصورة الشخصية فلا تحتاج لإعادة إنشائها إلا عند تغيير الصورة الأصلية.
