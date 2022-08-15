---
title: Page
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل صفحة من مستند PDF .
type: docs
weight: 5790
url: /ar/net/aspose.pdf/page/
---
## Page class

فئة تمثل صفحة من مستند PDF .

```csharp
public sealed class Page : IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | الحصول على مجموعة من خصائص الصفحة . |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | الحصول على مجموعة من التعليقات التوضيحية للصفحة . [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | الحصول على أو تعيين المربع الفني للصفحة. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | الحصول على مجموعة من القطع الأثرية على الصفحة. |
| [Background](../../aspose.pdf/page/background) { get; set; } | الحصول على أو تحديد لون خلفية الصفحة. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | الحصول على أو تعيين صورة الخلفية للصفحة (للمولد فقط). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | الحصول على أو تعيين مربع التسييل الخاص بالصفحة. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | يضبط نوع لون الصفحات بناءً على المعلومات التي يتم الحصول عليها من المشغلين SetColor ، الصور والنماذج . |
| [Contents](../../aspose.pdf/page/contents) { get; } | يحصل على مجموعة من العوامل في دفق محتوى الصفحة.[`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | الحصول على أو تعيين مربع اقتصاص الصفحة. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | الحصول على مدة عرض الصفحة المحددة. هذا هو الوقت بالثواني الذي سيتم عرض هذه الصفحة أثناء العرض التقديمي . Returs -1 إذا لم يتم تحديد المدة. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | الحصول على قائمة كائن الحقل بترتيب الجدولة في هذه الصفحة. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | الحصول على تذييل الصفحة أو تعيينه. |
| [Group](../../aspose.pdf/page/group) { get; set; } | الحصول على أو تعيين فئة سمات المجموعة التي تحدد سمات مجموعة الصفحات الخاصة بالصفحات لاستخدامها في نموذج التصوير الشفاف. |
| [Header](../../aspose.pdf/page/header) { get; set; } | الحصول على رأس الصفحة أو تعيينه. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | الحصول على أو تعيين إضافة الفقرات بعد الفقرة الأخيرة من الصفحة |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | الحصول على مجموعة طبقات أو تعيينها. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | الحصول على أو تعيين مربع وسائط الصفحة. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | الحصول على نمط الخط للملاحظات أو تعيينه. (للمولد فقط) |
| [Number](../../aspose.pdf/page/number) { get; } | احصل على رقم الصفحة . |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | الحصول على معلومات الصفحة أو تعيينها (للمولد فقط ، لا يتم ملؤها عند قراءة الملف). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | الحصول على الفقرات. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | الحصول على مستطيل الصفحة أو تعيينه. يتم إرجاع مربع اقتصاص الصفحة إذا تم تحديده ، وإلا يتم إرجاع مربع وسائط الصفحة . يرجى ملاحظة أن هذه الخاصية لا تأخذ في الاعتبار تدوير الصفحة. للحصول على مستطيل الصفحة الذي يفكر في التدوير ، يرجى استخدام ActualRect . |
| [Resources](../../aspose.pdf/page/resources) { get; } | يحصل على موارد الصفحة. يحتوي كائن الموارد على مجموعات من الصور والنماذج والخطوط.[`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | الحصول على تدوير الصفحة أو تعيينه. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | يحصل على مصفوفة التحويل للصفحة. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | الحصول على ترتيب الصفحة للصفحة أو تعيينه. القيم المحتملة: الصف والعمود. افتراضي ، Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | الحصول على معلومات جدول المحتويات أو تعيينها. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | الحصول على أو تعيين مربع القطع للصفحة. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | الحصول على أو تعيين قيمة UserUnit. رقم موجب يوضح حجم وحدات مساحة المستخدم الافتراضية ، بمضاعفات 1 72 بوصة. القيمة الافتراضية هي 1. يرجى تعيين قيمة صفرية أو سالبة لمسح هذا الإدخال في الصفحة . |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | الحصول على العلامة المائية للصفحة أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | يقبل[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) كائن زائر يوفر وظائف للعمل مع التعليقات التوضيحية. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | يقبل[`ImagePlacementAbsorber`](../imageplacementabsorber) كائن زائر يوفر وظائف للعمل مع كائنات وضع الصورة. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | يقبل[`TextAbsorber`](../../aspose.pdf.text/textabsorber) كائن زائر يوفر وظائف للعمل مع كائنات النص. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | يقبل[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) كائن زائر يوفر وظائف للعمل مع كائنات النص. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | يضيف صورة إلى الصفحة ويحددها في منتصف المستطيل المحدد لحفظ نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | يضيف صورة إلى الصفحة ويحددها في منتصف المستطيل المحدد لحفظ نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | يضيف صورة قابلة للبحث إلى الصفحة ويحددها في منتصف المستطيل المحدد لحفظ نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | يضيف صورة على الصفحة ويعتمد على موضع مستطيل الصورة. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | ضع الختم في الصفحة. يمكن أن يكون الطابع رقم صفحة أو صورة أو نصًا بسيطًا ، على سبيل المثال بعض الشعار. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | تحويل الصفحة الحالية إلى صورة نقطية وإرجاع مصفوفة من البايت. |
| [AsXml](../../aspose.pdf/page/asxml)() | تحويل الصفحة الحالية إلى xml بترميز utf8 . |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | حساب قيمة bbox - مستطيل يحتوي على محتويات بدون هوامش مرئية. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | قم بتحويل الصفحة إلى PNG لدفق صور DSR و OMR و OCR. |
| [Dispose](../../aspose.pdf/page/dispose)() | يحرر الذاكرة |
| [Flatten](../../aspose.pdf/page/flatten)() | يزيل كافة الحقول الموجودة على الصفحة ويضع قيمها بدلاً من ذلك. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | مسح البيانات المخزنة مؤقتًا |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | إرجاع إشعارات حول العمليات الداخلية مع محتوى الصفحة. (يتم دعم الإخطارات فقط حول أحداث الفقرة في سيناريوهات إضافة النص.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | إرجاع مستطيل الصفحة. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | يحصل على العلم سواء كانت الصفحة فارغة أم لا. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | يحول الصفحة إلى تدرج رمادي. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | يحدد حجم الصفحة للصفحة. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | يترجم قيمة العدد الصحيح إلى عضو تعداد تناوب مطابق. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | يترجم عضو التعداد بالتناوب إلى قيمة عدد صحيح. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | إجراء لتخصيص الرأس والتذييل . |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
