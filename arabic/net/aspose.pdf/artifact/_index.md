---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Artifact. تمثل الفئة كائن أثر PDF
type: docs
weight: 2770
url: /ar/net/aspose.pdf/artifact/
---
## فئة الأثر

تمثل الفئة كائن أثر PDF.

```csharp
public class Artifact : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | منشئ الأثر مع النوع والفرعي المحددين |
| [Artifact](artifact/#constructor_1)(string, string) | منشئ الأثر مع النوع والفرعي المحددين |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | المحاذاة الأفقية للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | المحاذاة الرأسية للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة من العمليات الداخلية للأثر. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم النوع الفرعي للأثر. قد يُستخدم إذا كان النوع الفرعي للأثر غير قياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع الأثر. قد يُستخدم إذا كان نوع الأثر غير قياسي. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للأثر (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة الأثر (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كانت صحيحة، يتم وضع الأثر خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | خطوط نص الأثر متعدد الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل على أو يحدد شفافية الأثر. القيم الممكنة تتراوح بين 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل على أو يحدد موضع الأثر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على مستطيل الأثر. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل على أو يحدد زاوية دوران الأثر. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على النوع الفرعي للأثر. إذا كان للأثر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص الأثر. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص الأثر. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع الأثر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس الأثر لتحسين الأداء. عادةً ما يتم تغيير عمليات الأثر في أي وقت تم فيه تغيير خاصية الأثر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير الأثر. لتجنب هذا التأثير، ضع جميع تحديثات الأثر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | التخلص من الأثر. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للأثر. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | إزالة القيمة المخصصة من الأثر. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في الأثر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | يحدد صورة الأثر. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | يحدد صورة الأثر. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | تعيين النص وخصائص النص للأثر. يسمح بتحديد عدة أسطر. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | يحدد ما هي السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | يحدد صفحة PDF التي يتم وضعها على صفحة المستند كأثر. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | يحدد نص الأثر. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | تعيين النص وخصائص النص للأثر. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | يحدد القيمة المخصصة للأثر. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | تعداد الأنواع الفرعية الممكنة للأثر. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | تعداد الأنواع الممكنة للأثر. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)