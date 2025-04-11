---
title: Class PaginationArtifact
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PaginationArtifact. تمثل فئة أساسية مجردة لقطع الترقيم في مستند
type: docs
weight: 8260
url: /ar/net/aspose.pdf/paginationartifact/
---
## PaginationArtifact class

تمثل فئة أساسية مجردة لقطع الترقيم في مستند.

```csharp
public abstract class PaginationArtifact : Artifact
```

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | المحاذاة الأفقية للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | المحاذاة الرأسية للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة من العمليات الداخلية للقطعة. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم نوع القطعة الفرعي. يمكن استخدامه إذا كان نوع القطعة الفرعي غير قياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع القطعة. يمكن استخدامه إذا كان نوع القطعة غير قياسي. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | يحصل على أو يحدد رقم الصفحة النهائية للقطعة. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، فسيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود لصفحة النهاية. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للقطعة (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة القطعة (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كانت القيمة صحيحة، يتم وضع القطعة خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | خطوط نص القطعة متعددة الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل على أو يحدد شفافية القطعة. القيم الممكنة تتراوح بين 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل على أو يحدد موضع القطعة. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على مستطيل القطعة. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل على أو يحدد زاوية دوران القطعة. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | يحصل على أو يحدد رقم الصفحة الابتدائية للقطعة. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، فسيتم تعديلها إلى 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | يحصل على أو يحدد مجموعة الصفحات التي تنطبق عليها القطعة (مثل، جميع الصفحات، الصفحات الزوجية، الصفحات الفردية). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على نوع القطعة الفرعي. إذا كانت القطعة تحتوي على نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص القطعة. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص القطعة. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للقطعة. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع القطعة. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس القطعة لتحسين الأداء. عادةً ما يتم تغيير عمليات القطعة في أي وقت تم فيه تغيير خاصية القطعة. وهذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير القطعة. لتجنب هذا التأثير، ضع جميع تحديثات القطعة بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | التخلص من القطعة. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للقطعة. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | إزالة القيمة المخصصة من القطعة. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في القطعة التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | تعيين صورة القطعة. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | تعيين صورة القطعة. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | تعيين النص وخصائص النص للقطعة. يسمح بتحديد عدة أسطر. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | تعيين ما هي السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | تعيين صفحة PDF التي توضع على صفحة المستند كقطعة. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | تعيين نص القطعة. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | تعيين النص وخصائص النص للقطعة. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | تعيين القيمة المخصصة للقطعة. |

### See Also

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)