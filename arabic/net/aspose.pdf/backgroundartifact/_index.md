---
title: BackgroundArtifact
second_title: Aspose.PDF لمرجع .NET API
description: وصف فئة الخلفية قطعة أثرية. تسمح هذه الأداة بتعيين خلفية الصفحة.
type: docs
weight: 1350
url: /ar/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class

وصف فئة الخلفية قطعة أثرية. تسمح هذه الأداة بتعيين خلفية الصفحة.

```csharp
public class BackgroundArtifact : Artifact
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BackgroundArtifact](backgroundartifact)() | تهيئة كائن BackgroundArtifact. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | المحاذاة الأفقية للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | المحاذاة الرأسية للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor) { get; set; } | الحصول على أو تعيين لون الخلفية من قطعة أثرية |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage) { get; set; } | الحصول على أو تعيين صورة خلفية لخلفية الأداة |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | الهامش السفلي للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | الحصول على مجموعة من عوامل التشغيل الداخلية المصنوعة يدويًا. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | الحصول على اسم النوع الفرعي للقطعة الأثرية. يمكن استخدامه إذا لم يكن النوع الفرعي للقطعة الأثرية هو النوع الفرعي القياسي. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | الحصول على اسم نوع الأداة. يمكن استخدامه إذا كان نوع الأداة غير قياسي. |
| [Form](../../aspose.pdf/artifact/form) { get; } | يحصل على XForm من الأداة (إذا تم استخدام XForm) . |
| [Image](../../aspose.pdf/artifact/image) { get; } | الحصول على صورة القطعة الأثرية (إذا كانت موجودة). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | إذا تم وضع الأداة الحقيقية خلف محتويات الصفحة. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | الهامش الأيسر للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | خطوط من قطعة أثرية للنص متعدد الأسطر. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | الحصول على عتامة الأداة أو تعيينها. القيم المحتملة في النطاق 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | الحصول على موضع الأداة أو تعيينه . إذا تم تحديد هذه الخاصية ، فسيتم تجاهل الهوامش والمحاذاة. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | يحصل على مستطيل القطعة الأثرية. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | الهامش الأيمن للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | الحصول على أو تعيين زاوية دوران الأداة. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | يحصل على النوع الفرعي الأداة. إذا كانت القطعة الأثرية تحتوي على نوع فرعي غير قياسي ، فيمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | الحصول على نص الأداة . |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | حالة النص للنص الاصطناعي. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | الهامش العلوي للقطعة الأثرية. إذا تم تحديد الموضع بشكل صريح (في خاصية الموضع) ، فسيتم تجاهل هذه القيمة. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | يحصل على نوع الأداة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | بدء التحديثات المؤجلة. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس الأداة لتحسين الأداء. عادةً ما يتم تغيير عوامل التشغيل الأثرية في أي وقت عند تغيير خاصية الأداة. يؤدي هذا إلى تغيير محتويات الصفحة في كل مرة يتم فيها تغيير الأداة. لتجنب هذا التأثير ، ضع جميع التحديثات الأثرية بين مكالمات StartUpdates / SaveUpdates . وهذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | تخلص من الأداة . |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | الحصول على قيمة مخصصة للقطعة الأثرية. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | إزالة القيمة المخصصة من الأداة. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | يحفظ كافة التحديثات في الأداة التي تم إجراؤها بعد استدعاء BeginUpdates (). |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | يحدد صورة القطعة الأثرية. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | يحدد صورة القطعة الأثرية. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | تعيين خصائص النص والنص للقطعة الأثرية. يسمح بتحديد خطوط متعددة. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | لتعيين صفحة PDF التي يتم وضعها على صفحة المستند على أنها قطعة أثرية. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | يحدد نص الأداة. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | تعيين خصائص النص والنص للقطعة الأثرية. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | يحدد قيمة مخصصة للقطعة الأثرية. |

### أنظر أيضا

* class [Artifact](../artifact)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
