---
title: "فئة Artifact"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Artifact. الفئة تمثل كائن PDF Artifact"
type: docs
weight: 2870
url: /ar/net/aspose.pdf/artifact/
---
## Artifact class

الفئة تمثل كائن PDF Artifact.

```csharp
public class Artifact : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | منشئ artifact مع النوع والنوع الفرعي المحددين |
| [Artifact](artifact/#constructor_1)(string, string) | منشئ artifact مع النوع والنوع الفرعي المحددين |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | محاذاة أفقية للقطعة. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | محاذاة رأسية للقطعة. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للقطعة. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة المشغلات الداخلية للقطعة. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم النوع الفرعي للقطعة. قد يُستخدم إذا كان النوع الفرعي للقطعة ليس نوعًا فرعيًا قياسيًا. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع القطعة. قد يُستخدم إذا كان نوع القطعة غير قياسي. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للقطعة (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة القطعة (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كان true فإن Artifact توضع خلف محتويات page. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للقطعة. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | أسطر قطعة النص متعدد الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل أو يضبط شفافية القطعة. القيم الممكنة في النطاق 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل أو يضبط موضع القطعة. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على Rectangle للقطعة. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للقطعة. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل أو يضبط زاوية دوران القطعة. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على النوع الفرعي للقطعة. إذا كان للقطعة نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص القطعة. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص القطعة. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع العنصر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | ابدأ التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة لإجراء عدة تغييرات على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلي العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | تخلص من العنصر. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للعنصر. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | إزالة القيمة المخصصة من العنصر. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في العنصر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | يضبط صورة العنصر. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | يضبط صورة العنصر. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | يضبط النص وخصائص النص للعنصر. يسمح بتحديد عدة أسطر. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | يضبط السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | يضبط صفحة PDF التي توضع على صفحة Document كعنصر. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | يضبط نص العنصر. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | يضبط نص العنصر وخصائص النص. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | يضبط القيمة المخصصة للعنصر. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | تعداد الأنواع الفرعية الممكنة لـ artifacts. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | تعداد لأنواع القطع الفنية الممكنة. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


