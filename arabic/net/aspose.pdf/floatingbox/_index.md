---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.FloatingBox.
type: docs
weight: 4870
url: /ar/net/aspose.pdf/floatingbox/
---
## فئة FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | يقوم بتهيئة مثيل جديد من فئة `FloatingBox` مع عرض وارتفاع محددين. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | يحصل أو يحدد كائن [`Color`](../color/) الذي يشير إلى لون خلفية صندوق العائم. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | يحصل أو يحدد صورة الخلفية للصفحة (للمولد فقط، لا يتم ملؤها عند قراءة المستند). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | يحصل أو يحدد كائن [`BorderInfo`](../borderinfo/) الذي يشير إلى معلومات الحدود لصندوق العائم. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | يحصل أو يحدد معلومات العمود |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | يحصل أو يحدد قيمة عائمة تشير إلى ارتفاع صندوق العائم. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الفقرة (للمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة بحاجة إلى التكرار في الصفحة التالية. القيمة الافتراضية هي false. السمة صالحة فقط عندما تكون الفقرة نفسها والكائن الذي يشير إليه ReferenceParagraphID مدرجين في RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | يحصل أو يحدد إحداثي اليسار للجدول. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | يحصل أو يحدد كائن [`MarginInfo`](../margininfo/) الذي يشير إلى الحشو لصندوق العائم. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | يحصل أو يحدد مجموعة [`Paragraphs`](./paragraphs/) التي تشير إلى جميع الفقرات في الخلية. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | يحدد متغيرًا لتحديد موقع صندوق العائم على الصفحة. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | يحصل أو يحدد إحداثي الأعلى للجدول. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | يحصل أو يحدد قيمة عائمة تشير إلى عرض صندوق العائم. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | يقوم بإنشاء نسخة جديدة من كائن `FloatingBox`. الفقرات في صندوق العائم لا يتم نسخها. |

### انظر أيضًا

* فئة [BaseParagraph](../baseparagraph/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)