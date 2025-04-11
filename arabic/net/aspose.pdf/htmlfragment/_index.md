---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.HtmlFragment. تمثل جزء HTML
type: docs
weight: 5520
url: /ar/net/aspose.pdf/htmlfragment/
---
## فئة HtmlFragment

تمثل جزء HTML.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | يقوم بتهيئة مثيل جديد من فئة HtmlFragment. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية للفقرة |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | يحصل أو يحدد HtmlLoadOptions التي ستستخدم لتحميل (ورسم) HTML في هذا المثيل من الفئة. يرجى استخدامه عند الحاجة إلى استخدام إعدادات محددة لاستيراد HTML لهذا أو ذاك المثيل (على سبيل المثال، عندما يجب أن يستخدم هذا أو ذاك المثيل مسار قاعدة محدد لـ HTML المستورد أو يجب أن يستخدم محمل محدد للموارد الخارجية) إذا كان المعامل هو الافتراضي (null)، فسيتم استخدام خيارات تحميل HTML القياسية. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (لإنشاء PDF). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | يحصل أو يحدد كسر الكلمات |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. الافتراضي هو false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. الافتراضي هو false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. الافتراضي هو false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. الافتراضي هو false. (لإنشاء PDF) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة تحتوي على هامش افتراضي، وإلا فإن الهامش هو 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | يحصل على مستطيل HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | يحصل أو يحدد الخط |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم مع ZIndex أكبر فوق الرسم مع ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم مع ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | يقوم باستنساخ جزء HTML. |

### انظر أيضًا

* فئة [FormattedFragment](../formattedfragment/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)