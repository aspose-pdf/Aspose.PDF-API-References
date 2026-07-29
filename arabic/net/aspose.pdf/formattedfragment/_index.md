---
title: "الفئة FormattedFragment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.FormattedFragment. تمثل جزءًا منسقًا تجريديًا"
type: docs
weight: 5060
url: /ar/net/aspose.pdf/formattedfragment/
---
## FormattedFragment class

يمثل قطعة منسقة مجردة.

```csharp
public abstract class FormattedFragment : BaseParagraph
```

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
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |

### انظر أيضًا

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


