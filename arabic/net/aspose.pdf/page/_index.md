---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Page. فئة تمثل صفحة من مستند PDF
type: docs
weight: 8050
url: /ar/net/aspose.pdf/page/
---
## فئة الصفحة

فئة تمثل صفحة من مستند PDF.

```csharp
public sealed class Page : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [الإجراءات](../../aspose.pdf/page/actions/) { get; } | يحصل على مجموعة من خصائص الصفحة. |
| [التعليقات التوضيحية](../../aspose.pdf/page/annotations/) { get; } | يحصل على مجموعة من التعليقات التوضيحية للصفحة. [`التعليقات التوضيحية`](./annotations/) |
| [صندوق الفن](../../aspose.pdf/page/artbox/) { get; set; } | يحصل أو يحدد صندوق الفن للصفحة. |
| [القطع الأثرية](../../aspose.pdf/page/artifacts/) { get; } | يحصل على مجموعة من القطع الأثرية على الصفحة. |
| [الخلفية](../../aspose.pdf/page/background/) { get; set; } | يحصل أو يحدد لون الخلفية للصفحة. |
| [صورة الخلفية](../../aspose.pdf/page/backgroundimage/) { get; set; } | يحصل أو يحدد صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [صندوق النزيف](../../aspose.pdf/page/bleedbox/) { get; set; } | يحصل أو يحدد صندوق النزيف للصفحة. |
| [نوع اللون](../../aspose.pdf/page/colortype/) { get; } | يحدد نوع اللون للصفحات بناءً على المعلومات المستمدة من المشغلين SetColor، الصور والنماذج. |
| [المحتويات](../../aspose.pdf/page/contents/) { get; } | يحصل على مجموعة من المشغلين في تدفق محتوى الصفحة. [`مجموعة المشغلين`](../operatorcollection/) |
| [صندوق القص](../../aspose.pdf/page/cropbox/) { get; set; } | يحصل أو يحدد صندوق القص للصفحة. |
| [المدة](../../aspose.pdf/page/duration/) { get; set; } | يحصل أو يحدد مدة عرض الصفحة. هذه هي المدة بالثواني التي يجب عرض الصفحة خلالها أثناء العرض. تعيد -1 إذا لم يتم تعريف المدة. |
| [الحقول في ترتيب التبويب](../../aspose.pdf/page/fieldsintaborder/) { get; } | يحصل على قائمة من كائنات الحقول في ترتيب التبويب على هذه الصفحة. |
| [التذييل](../../aspose.pdf/page/footer/) { get; set; } | يحصل أو يحدد تذييل الصفحة. |
| [المجموعة](../../aspose.pdf/page/group/) { get; set; } | يحصل أو يحدد فئة سمات المجموعة التي تحدد سمات مجموعة الصفحة لاستخدامها في نموذج التصوير الشفاف. |
| [الرأس](../../aspose.pdf/page/header/) { get; set; } | يحصل أو يحدد رأس الصفحة. |
| [هل إضافة فقرات بعد الأخيرة](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | يحصل أو يحدد إضافة الفقرات بعد آخر فقرة في الصفحة |
| [الطبقات](../../aspose.pdf/page/layers/) { get; set; } | يحصل أو يحدد مجموعة الطبقات. |
| [صندوق الوسائط](../../aspose.pdf/page/mediabox/) { get; set; } | يحصل أو يحدد صندوق الوسائط للصفحة. |
| [نمط خط الملاحظة](../../aspose.pdf/page/notelinestyle/) { get; set; } | يحصل أو يحدد نمط الخط للملاحظات. (للمولد فقط، لا يتم ملؤها عند قراءة المستند) |
| [الرقم](../../aspose.pdf/page/number/) { get; } | يحصل على رقم الصفحة. |
| [معلومات الصفحة](../../aspose.pdf/page/pageinfo/) { get; set; } | يحصل أو يحدد معلومات الصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [الفقرات](../../aspose.pdf/page/paragraphs/) { get; set; } | يحصل على الفقرات. |
| [المستطيل](../../aspose.pdf/page/rect/) { get; set; } | يحصل أو يحدد مستطيل الصفحة. للحصول على: يتم إرجاع صندوق القص للصفحة إذا تم تحديده، وإلا يتم إرجاع صندوق الوسائط للصفحة. للتعيين: يتم دائمًا تعيين صندوق الوسائط للصفحة. يرجى ملاحظة أن هذه الخاصية لا تأخذ في الاعتبار دوران الصفحة. للحصول على مستطيل الصفحة مع الأخذ في الاعتبار الدوران، يرجى استخدام ActualRect. |
| [الموارد](../../aspose.pdf/page/resources/) { get; } | يحصل على موارد الصفحة. يحتوي كائن الموارد على مجموعات من الصور والنماذج والخطوط. [`الموارد`](./resources/) |
| [الدوران](../../aspose.pdf/page/rotate/) { get; set; } | يحصل أو يحدد دوران الصفحة. |
| [مصفوفة الدوران](../../aspose.pdf/page/rotationmatrix/) { get; } | يحصل على مصفوفة التحويل للصفحة. |
| [ترتيب التبويب](../../aspose.pdf/page/taborder/) { get; set; } | يحصل أو يحدد ترتيب التبويب للصفحة. القيم الممكنة: صف، عمود. الافتراضي، يدوي |
| [معلومات جدول المحتويات](../../aspose.pdf/page/tocinfo/) { get; set; } | يحصل أو يحدد معلومات جدول المحتويات. |
| [صندوق القص](../../aspose.pdf/page/trimbox/) { get; set; } | يحصل أو يحدد صندوق القص للصفحة. |
| [وحدة المستخدم](../../aspose.pdf/page/userunit/) { get; set; } | يحصل أو يحدد قيمة وحدة المستخدم. رقم موجب يعطي حجم وحدات مساحة المستخدم الافتراضية، بمضاعفات 1 / 72 بوصة. القيمة الافتراضية هي 1. يرجى تعيين قيمة صفر أو سلبية من أجل مسح هذا الإدخال في الصفحة. |
| [علامة مائية](../../aspose.pdf/page/watermark/) { get; set; } | يحصل أو يحدد العلامة المائية للصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [قبول](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | يقبل كائن الزائر [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) الذي يوفر وظائف للعمل مع التعليقات التوضيحية. |
| [قبول](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | يقبل كائن الزائر [`ImagePlacementAbsorber`](../imageplacementabsorber/) الذي يوفر وظائف للعمل مع كائنات وضع الصورة. |
| [قبول](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | يقبل كائن الزائر [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) الذي يوفر وظائف للعمل مع كائنات النص. |
| [قبول](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | يقبل كائن الزائر [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) الذي يوفر وظائف للعمل مع كائنات النص. |
| [إضافة رسومات](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | يضيف رسومات إلى الصفحة. يعمل بشكل أسرع من إضافة العناصر واحدة تلو الأخرى باستخدام طريقة [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [إضافة صورة](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | يضيف صورة إلى الصفحة ويضعها في منتصف المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [إضافة صورة](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | يضيف صورة إلى الصفحة ويضعها في منتصف المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [إضافة صورة](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | يضيف صورة قابلة للبحث إلى الصفحة ويضعها في منتصف المستطيل المحدد مع الحفاظ على نسبة الصورة. |
| [إضافة صورة](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | يضيف صورة إلى الصفحة ويضعها بناءً على موضع مستطيل الصورة. |
| [إضافة ختم](../../aspose.pdf/page/addstamp/)(Stamp) | يضع ختمًا في الصفحة. يمكن أن يكون الختم رقم الصفحة أو صورة أو نص بسيط، مثل شعار ما. |
| [كـ مصفوفة بايت](../../aspose.pdf/page/asbytearray/)(Resolution) | يحول الصفحة الحالية إلى صورة نقطية ثم يعيد مصفوفة من البايتات. |
| [كـ XML](../../aspose.pdf/page/asxml/)() | يحول الصفحة الحالية إلى XML بتشفير UTF-8. |
| [حساب bbox المحتوى](../../aspose.pdf/page/calculatecontentbbox/)() | يحسب قيمة bbox - مستطيل يحتوي على المحتويات بدون هوامش مرئية. |
| [تحويل إلى دفق PNG في الذاكرة](../../aspose.pdf/page/converttopngmemorystream/)() | تحويل الصفحة إلى PNG لدفق صورة DSR، OMR، OCR. |
| [حذف الرسومات](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | يحذف الرسومات من الصفحة. يعمل بشكل أسرع من حذف العناصر واحدة تلو الأخرى باستخدام طريقة [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [تخلص](../../aspose.pdf/page/dispose/)() | يحرر الذاكرة |
| [تسطح](../../aspose.pdf/page/flatten/)() | يزيل جميع الحقول الموجودة على الصفحة ويضع قيمها بدلاً من ذلك. |
| [تحرير الذاكرة](../../aspose.pdf/page/freememory/)() | يمسح البيانات المخزنة مؤقتًا |
| [الحصول على الإشعارات](../../aspose.pdf/page/getnotifications/)() | يعيد الإشعارات حول العمليات الداخلية مع محتوى الصفحة. (فقط الإشعارات حول أحداث الفقرات في سيناريوهات إضافة النص مدعومة الآن.) |
| [الحصول على مستطيل الصفحة](../../aspose.pdf/page/getpagerect/)(bool) | يعيد مستطيل الصفحة وفقًا لصندوق القص الخاص بها (أو صندوق الوسائط إذا كان صندوق القص فارغًا). |
| [الحصول على الموارد](../../aspose.pdf/page/getresources/)() | يسترجع الموارد المرتبطة بالصفحة. |
| [هل تحتوي على رسومات متجهة](../../aspose.pdf/page/hasvectorgraphics/)() | يكشف عن وجود رسومات متجهة، إذا كانت موجودة على الصفحة. |
| [هل فارغة](../../aspose.pdf/page/isblank/)(double) | يحصل على العلم ما إذا كانت الصفحة فارغة أم لا. |
| [اجعلها بالأبيض والأسود](../../aspose.pdf/page/makegrayscale/)() | يحول الصفحة إلى الأبيض والأسود. |
| [دمج الطبقات](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | يدمج جميع الطبقات على الصفحة في طبقة واحدة بالاسم الجديد المحدد. |
| [دمج الطبقات](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | يدمج جميع الطبقات على الصفحة في طبقة واحدة بالاسم الجديد المحدد ومعرف مجموعة المحتوى الاختياري. |
| [تغيير الحجم](../../aspose.pdf/page/resize/)(PageSize) | يغير حجم الصفحة. |
| [إرسال إلى](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | يرسل الصفحة للمعالجة مع جهاز الصفحة المحدد. |
| [إرسال إلى](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | يرسل الصفحة للمعالجة مع جهاز الصفحة المحدد. |
| [تعيين حجم الصفحة](../../aspose.pdf/page/setpagesize/)(double, double) | يحدد حجم الصفحة للصفحة. |
| [محاولة حفظ الرسومات المتجهة](../../aspose.pdf/page/trysavevectorgraphics/)(string) | يحاول حفظ الرسومات المتجهة إذا كانت موجودة على الصفحة. تنسيق الحفظ هو SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | يترجم القيمة الصحيحة إلى عضو التعداد المقابل للدوران. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | يترجم عضو التعداد للدوران إلى قيمة صحيحة. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| الحدث [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | حدث لتخصيص الرأس والتذييل. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | إجراء لتخصيص الرأس والتذييل. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)