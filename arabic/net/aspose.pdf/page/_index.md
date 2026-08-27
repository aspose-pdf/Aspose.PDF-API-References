---
title: "فئة Page"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Page. فئة تمثل صفحة من مستند PDF"
type: docs
weight: 8190
url: /ar/net/aspose.pdf/page/
---
## Page class

فئة تمثل صفحة من مستند PDF.

```csharp
public sealed class Page : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | يحصل على مجموعة خصائص الصفحة. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | يحصل على مجموعة تعليقات الصفحة. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | يحصل أو يضبط صندوق الفن للصفحة. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | يحصل على مجموعة القطع الأثرية في الصفحة. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | يحصل أو يضبط لون الخلفية للصفحة. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | يحصل أو يعيّن صورة الخلفية للصفحة (للمولد فقط، لا تُملأ عند قراءة المستند). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | يحصل أو يضبط صندوق النزف للصفحة. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | يضبط نوع اللون للصفحات بناءً على المعلومات المستلمة من المشغلات SetColor، الصور والنماذج. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | يحصل على مجموعة المشغلات في تدفق المحتوى للصفحة. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | يحصل أو يضبط صندوق القص للصفحة. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | يحصل أو يضبط مدة عرض الصفحة. هذه هي الوقت بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. يُرجع -1 إذا لم يتم تعريف المدة. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | يحصل على قائمة كائنات Field بترتيب Tab في هذه الصفحة. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | يحصل أو يضبط تذييل الصفحة. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | يحصل أو يضبط فئة سمات المجموعة التي تحدد سمات مجموعة الصفحة للاستخدام في نموذج التصوير الشفاف. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | يحصل أو يضبط رأس الصفحة. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | يحصل أو يضبط إضافة الفقرات بعد الفقرة الأخيرة في الصفحة |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | يحصل أو يضبط مجموعة الطبقات. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | يحصل أو يضبط صندوق الوسائط للصفحة. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | يحصل أو يضبط نمط الخط للملاحظات. (للمولد فقط، لا يتم ملؤه عند قراءة المستند) |
| [Number](../../aspose.pdf/page/number/) { get; } | احصل على رقم الصفحة. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | يحصل أو يضبط معلومات الصفحة (للمولد فقط، لا يتم ملؤه عند قراءة المستند). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | يحصل على الفقرات. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | يحصل أو يضبط مستطيل الصفحة. عند الحصول: يتم إرجاع صندوق القص إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط. عند الضبط: يتم دائمًا ضبط صندوق الوسائط. يرجى ملاحظة أن هذه الخاصية لا تأخذ دوران الصفحة في الاعتبار. للحصول على مستطيل الصفحة مع مراعاة الدوران يرجى استخدام ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | يحصل على موارد الصفحة. كائن Resources يحتوي على مجموعات من الصور والنماذج والخطوط. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | يحصل أو يضبط دوران الصفحة. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | يحصل على مصفوفة التحويل للصفحة. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | يحصل أو يضبط ترتيب التبويب للصفحة. القيم الممكنة: Row, Column. الافتراضي، Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | يحصل أو يضبط معلومات جدول المحتويات. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | يحصل أو يضبط صندوق القص للصفحة. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | يحصل أو يضبط قيمة UserUnit. رقم موجب يحدد حجم وحدات مساحة المستخدم الافتراضية، بمضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى ضبط صفر أو قيمة سالبة لمسح هذا الإدخال في الصفحة. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | يحصل أو يضبط العلامة المائية للصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | يقبل كائن الزائر [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) الذي يوفر وظيفة للعمل مع التعليقات التوضيحية. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | يقبل كائن الزائر [`ImagePlacementAbsorber`](../imageplacementabsorber/) الذي يوفر وظيفة للعمل مع كائنات وضع الصور. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | يقبل كائن الزائر [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) الذي يوفر وظيفة للعمل مع كائنات النص. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | يقبل كائن الزائر [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) الذي يوفر وظيفة للعمل مع كائنات النص. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | يضيف الرسومات إلى الصفحة. يعمل أسرع من إضافة العناصر واحدةً تلو الأخرى باستخدام طريقة [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | يضيف صورة إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في وسط المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | يضيف صورة إلى الصفحة ويضعها اعتمادًا على موضع مستطيل الصورة. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | يضع ختمًا في الصفحة. يمكن أن يكون الختم رقم الصفحة أو صورة أو نصًا بسيطًا، مثل شعار ما. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | يحول الصفحة الحالية إلى صورة نقطية ثم يُعيد مصفوفة من البايتات. |
| [AsXml](../../aspose.pdf/page/asxml/)() | يحول الصفحة الحالية إلى XML بترميز UTF-8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | يحسب قيمة bbox - المستطيل الذي يحتوي على المحتوى دون الهوامش المرئية. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | يحذف الرسومات من الصفحة. يعمل أسرع من حذف العناصر واحدةً تلو الأخرى باستخدام طريقة [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | يفرغ الذاكرة |
| [Flatten](../../aspose.pdf/page/flatten/)() | يزيل جميع الحقول الموجودة على الصفحة ويضع قيمها بدلاً منها. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | يمسح البيانات المخزنة مؤقتًا |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | يعيد الإشعارات حول العمليات الداخلية مع محتوى الصفحة. (يتم دعم الإشعارات حول أحداث الفقرات في سيناريوهات إضافة النص فقط حاليًا.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | يعيد مستطيل الصفحة وفقًا لـ CropBox الخاص به (أو MediaBox إذا كان CropBox فارغًا). |
| [GetResources](../../aspose.pdf/page/getresources/)() | يسترجع الموارد المرتبطة بالصفحة. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | يكشف عن وجود الرسومات المتجهية إذا كانت موجودة في الصفحة. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | يحصل على العلامة التي تشير ما إذا كانت الصفحة فارغة أم لا. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | يحول الصفحة إلى تدرجات الرمادي. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | يدمج جميع الطبقات في الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة ومعرف مجموعة المحتوى الاختياري. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | يعيد تحجيم الصفحة. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | يرسل الصفحة للمعالجة باستخدام جهاز الصفحة المحدد. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | يضبط حجم الصفحة للصفحة. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | يحاول حفظ الرسومات المتجهية إذا كانت موجودة على الصفحة. صيغة الحفظ هي SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | يحوّل القيمة الصحيحة إلى عضو التعداد المتعلق بالدوران. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | يحوّل عضو التعداد المتعلق بالدوران إلى قيمة صحيحة. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | حدث لتخصيص الترويسة والتذييل. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | إجراء لتخصيص الترويسة والتذييل. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


