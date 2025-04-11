---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXFragment class. يمثل جزء TeX
type: docs
weight: 10360
url: /ar/net/aspose.pdf/texfragment/
---
## TeXFragment class

يمثل جزء TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | يقوم بتهيئة مثيل جديد من فئة HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | يقوم بتهيئة مثيل جديد من فئة HtmlFragment. |

## Properties

| Name | Description |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (لإنشاء PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | يحصل أو يحدد خيارات تحميل TeX التي ستستخدم لتحميل (ورسم) LaTeX في هذا المثيل من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعدادات محددة لاستيراد LaTeX لهذا أو ذاك المثيل (على سبيل المثال، عندما يجب أن يستخدم هذا أو ذاك المثيل مسار قاعدة محدد لـ LaTeX المستورد أو يجب أن يستخدم محملًا محددًا للموارد الخارجية) إذا كانت المعلمة افتراضية (null)، فسيتم استخدام خيارات تحميل LaTeX القياسية. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | يقوم باستنساخ الجزء. |

### See Also

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)