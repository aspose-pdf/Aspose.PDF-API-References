---
title: Class BackgroundArtifact
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.BackgroundArtifact. تصف هذه الفئة الأثر الخلفي. يسمح هذا الأثر بتعيين خلفية الصفحة
type: docs
weight: 2810
url: /ar/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class

تصف هذه الفئة الأثر الخلفي. يسمح هذا الأثر بتعيين خلفية الصفحة.

```csharp
public class BackgroundArtifact : Artifact
```

## Constructors

| Name | Description |
| --- | --- |
| [BackgroundArtifact](backgroundartifact/)() | يقوم بتهيئة كائن BackgroundArtifact. |

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | المحاذاة الأفقية للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | المحاذاة الرأسية للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor/) { get; set; } | يحصل أو يحدد لون الخلفية للأثر الخلفي |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage/) { get; set; } | يحصل أو يحدد صورة الخلفية للأثر الخلفي |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | الهامش السفلي للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | يحصل على مجموعة من العمليات الداخلية للأثر. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | يحصل على اسم نوع الأثر الفرعي. يمكن استخدامه إذا كان نوع الأثر الفرعي غير قياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | يحصل على اسم نوع الأثر. يمكن استخدامه إذا كان نوع الأثر غير قياسي. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | يحصل على XForm للأثر (إذا تم استخدام XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | يحصل على صورة الأثر (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | إذا كانت القيمة صحيحة، يتم وضع الأثر خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | الهامش الأيسر للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | خطوط الأثر النصي متعدد الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | يحصل أو يحدد شفافية الأثر. القيم الممكنة تتراوح بين 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | يحصل أو يحدد موضع الأثر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | يحصل على مستطيل الأثر. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | الهامش الأيمن للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | يحصل أو يحدد زاوية دوران الأثر. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | يحصل على نوع الأثر الفرعي. إذا كان للأثر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | يحصل على نص الأثر. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | حالة النص لنص الأثر. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | الهامش العلوي للأثر. إذا تم تحديد الموضع بشكل صريح (في خاصية Position) يتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | يحصل على نوع الأثر. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء تغييرات متعددة على نفس الأثر لتحسين الأداء. عادةً ما يتم تغيير عمليات الأثر في أي وقت تم فيه تغيير خاصية الأثر. هذا يتسبب في تغيير محتويات الصفحة في كل مرة يتم فيها تغيير الأثر. لتجنب هذا التأثير، ضع جميع تحديثات الأثر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | يتخلص من الأثر. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | يحصل على القيمة المخصصة للأثر. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | يزيل القيمة المخصصة من الأثر. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | يحفظ جميع التحديثات في الأثر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | يحدد صورة الأثر. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | يحدد صورة الأثر. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | يحدد النص وخصائص النص للأثر. يسمح بتحديد عدة أسطر. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | يحدد ما هي السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | يحدد صفحة PDF التي يتم وضعها على صفحة المستند كأثر. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | يحدد نص الأثر. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | يحدد النص وخصائص النص للأثر. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | يحدد القيمة المخصصة للأثر. |

### See Also

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)