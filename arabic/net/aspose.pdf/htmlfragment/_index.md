---
title: "الفئة HtmlFragment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.HtmlFragment. تمثل جزء html."
type: docs
weight: 5650
url: /ar/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

يمثل قطعة html.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | تهيئ كائنًا جديدًا من الفئة HtmlFragment. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية للفقرة |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | الحصول أو الضبط لـ HtmlLoadOptions التي ستُستخدم لتحميل (وعرض) HTML داخل هذا الكائن من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد HTML لهذا الكائن أو ذاك (مثلاً عندما يجب على هذا الكائن أو ذاك استخدام BasePath محدد لـ HTML المستورد أو يجب استخدام محمّل موارد خارجية محدد). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل HTML القياسية. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | الحصول أو الضبط لكسر الكلمات |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | الحصول أو الضبط لتحديد ما إذا كانت الفقرة تحتوي على هوامش افتراضية، وإلا تكون الهوامش 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | الحصول على المستطيل الخاص بـ HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | الحصول أو الضبط للخط |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | ينسخ جزء html. |

### انظر أيضًا

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


