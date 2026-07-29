---
title: "الفئة FloatingBox"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.FloatingBox."
type: docs
weight: 4990
url: /ar/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | ينشئ نسخة جديدة من الفئة `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | ينشئ نسخة جديدة من الفئة `FloatingBox` بالعرض والارتفاع المحددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | يحصل أو يعيّن كائن [`Color`](../color/) الذي يحدد لون خلفية الصندوق العائم. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | يحصل أو يعيّن صورة الخلفية للصفحة (للمولد فقط، لا تُملأ عند قراءة المستند). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | يحصل أو يعيّن كائن [`BorderInfo`](../borderinfo/) الذي يحدد معلومات حدود الصندوق العائم. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | يحصل أو يعيّن معلومات العمود |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | يحصل أو يعيّن قيمة عائمة تحدد ارتفاع الصندوق العائم. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | يحصل أو يعيّن قيمة منطقية تحدد ما إذا كان الفقرة تحتاج إلى التكرار في الصفحة التالية. القيمة الافتراضية هي false. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | يحصل أو يعيّن إحداثي اليسار للجدول. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | يحصل أو يعيّن كائن [`MarginInfo`](../margininfo/) الذي يحدد الحشو داخل الصندوق العائم. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | يحصل أو يعيّن مجموعة [`Paragraphs`](./paragraphs/) التي تحدد جميع الفقرات في الخلية. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | يحدد المتغير لتحديد موقع FloatingBox على الصفحة. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | يحصل أو يعيّن إحداثي أعلى الجدول. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | يحصل أو يعيّن قيمة عائمة تحدد عرض الصندوق العائم. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | ينسخ كائن `FloatingBox` جديد. الفقرات داخل الصندوق العائم لا تُنسخ. |

### انظر أيضًا

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


