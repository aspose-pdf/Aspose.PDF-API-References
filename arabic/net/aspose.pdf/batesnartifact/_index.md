---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.BatesNArtifact. تصف الفئة عنصر ترقيم بايتس
type: docs
weight: 2850
url: /ar/net/aspose.pdf/batesnartifact/
---
## BatesNArtifact class

تصف الفئة عنصر ترقيم بايتس.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Constructors

| Name | Description |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | Initializes a new instance of the `BatesNArtifact` class. هذه الباني داخلية وتقوم بإنشاء مثيل عنصر رأس بقيم افتراضية. |

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | المحاذاة الأفقية للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | المحاذاة الرأسية للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة من العمليات الداخلية للعنصر. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم نوع العنصر الفرعي. يمكن استخدامه إذا كان نوع العنصر الفرعي غير قياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع العنصر. يمكن استخدامه إذا كان نوع العنصر غير قياسي. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | يحصل على أو يحدد رقم الصفحة النهائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 0. إذا تم تعيين قيمة أقل من 0، فسيتم تعديلها إلى 0. القيمة الافتراضية 0 تعني عدم وجود حدود لصفحة النهاية. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للعنصر (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة العنصر (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كانت القيمة صحيحة، يتم وضع العنصر خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | خطوط نص العنصر متعدد الأسطر. |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | يحصل على أو يحدد عدد الأرقام لترقيم بايتس. يجب أن تكون القيمة بين 3 و 15 شاملة. إذا تم تعيين قيمة أقل من 3، فسيتم تعديلها إلى 3. إذا تم تعيين قيمة أكبر من 15، فسيتم تعديلها إلى 15. القيمة الافتراضية هي 6. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل على أو يحدد شفافية العنصر. القيم الممكنة تتراوح بين 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل على أو يحدد موضع العنصر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | يحصل على أو يحدد البادئة التي ستضاف إلى رقم بايتس. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على مستطيل العنصر. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل على أو يحدد زاوية دوران العنصر. |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | يحصل على أو يحدد الرقم الابتدائي لترقيم بايتس. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، فسيتم تعديلها إلى 1. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | يحصل على أو يحدد رقم الصفحة الابتدائية للعنصر. يجب أن تكون القيمة أكبر من أو تساوي 1. إذا تم تعيين قيمة أقل من 1، فسيتم تعديلها إلى 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | يحصل على أو يحدد مجموعة الصفحات التي ينطبق عليها العنصر (مثل، جميع الصفحات، الصفحات الزوجية، الصفحات الفردية). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على نوع العنصر الفرعي. إذا كان للعنصر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | يحصل على أو يحدد اللاحقة التي ستضاف إلى رقم بايتس. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص العنصر. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص العنصر. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للعنصر. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع العنصر. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير عمليات العنصر في أي وقت تم فيه تغيير خاصية العنصر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير العنصر. لتجنب هذا التأثير، ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | التخلص من العنصر. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للعنصر. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | إزالة القيمة المخصصة من العنصر. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في العنصر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | تعيين صورة العنصر. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | تعيين صورة العنصر. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | تعيين النص وخصائص النص للعنصر. يسمح بتحديد عدة أسطر. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | تعيين ما هي السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | تعيين صفحة PDF التي يتم وضعها على صفحة المستند كعنصر. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | تعيين نص العنصر. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | تعيين النص وخصائص النص للعنصر. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | تعيين القيمة المخصصة للعنصر. |

### See Also

* class [PaginationArtifact](../paginationartifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)