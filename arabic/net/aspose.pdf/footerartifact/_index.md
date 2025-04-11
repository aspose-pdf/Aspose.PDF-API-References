---
title: Class FooterArtifact
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.FooterArtifact. تصف عنصر التذييل. يمكن استخدام هذا لتعيين تذييل الصفحة
type: docs
weight: 4930
url: /ar/net/aspose.pdf/footerartifact/
---
## FooterArtifact class

تصف عنصر التذييل. يمكن استخدام هذا لتعيين تذييل الصفحة.

```csharp
public class FooterArtifact : Artifact
```

## Constructors

| Name | Description |
| --- | --- |
| [FooterArtifact](footerartifact/)() | ينشئ مثيل عنصر التذييل. |

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | المحاذاة الأفقية للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | المحاذاة الرأسية للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة من العمليات الداخلية للعنصر. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم نوع العنصر الفرعي. يمكن استخدامه إذا كان نوع العنصر الفرعي غير قياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع العنصر. يمكن استخدامه إذا كان نوع العنصر غير قياسي. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للعنصر (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة العنصر (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كانت القيمة صحيحة، يتم وضع العنصر خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | خطوط عنصر النص المتعدد الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل على أو يحدد شفافية العنصر. القيم الممكنة تتراوح بين 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل على أو يحدد موضع العنصر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على مستطيل العنصر. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل على أو يحدد زاوية دوران العنصر. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على نوع العنصر الفرعي. إذا كان للعنصر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص العنصر. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص العنصر. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع العنصر. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير عمليات العنصر في أي وقت تم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير، ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | التخلص من العنصر. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للعنصر. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | يزيل القيمة المخصصة من العنصر. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في العنصر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | يحدد صورة العنصر. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | يحدد صورة العنصر. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | يحدد النص وخصائص النص للعنصر. يسمح بتحديد عدة خطوط. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | يحدد ما هي السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | يحدد صفحة PDF التي يتم وضعها على صفحة المستند كعنصر. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | يحدد نص العنصر. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | يحدد النص وخصائص النص للعنصر. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | يحدد القيمة المخصصة للعنصر. |

### See Also

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)