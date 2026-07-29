---
title: "الفئة TeXFragment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.TeXFragment. تمثل شظية TeX"
type: docs
weight: 10540
url: /ar/net/aspose.pdf/texfragment/
---
## TeXFragment class

يمثل جزء TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | تهيئ كائنًا جديدًا من الفئة HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | تهيئ كائنًا جديدًا من الفئة HtmlFragment. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | يحصل أو يعيّن TeXLoadOptions التي ستُستخدم لتحميل (وتصيير) LaTeX إلى هذه النسخة من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد LaTeX لهذه أو لتلك النسخة (على سبيل المثال عندما يجب على هذه أو تلك النسخة استخدام BasePath محدد لـ LaTeX المستورد أو يجب استخدامها محمل موارد خارجية محدد). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل LaTeX القياسية. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | ينسخ الشظية. |

### انظر أيضًا

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


