---
title: "الفئة TextState"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Text.TextState. تمثل حالة نص"
type: docs
weight: 11260
url: /ar/net/aspose.pdf.text/textstate/
---
## TextState class

يمثل حالة نصية للنص

```csharp
public class TextState
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextState](textstate/#constructor)() | ينشئ كائن حالة النص. |
| [TextState](textstate/#constructor_2)(Color) | ينشئ كائن حالة النص مع تحديد لون المقدمة. |
| [TextState](textstate/#constructor_1)(double) | ينشئ كائن حالة النص مع تحديد حجم الخط. |
| [TextState](textstate/#constructor_4)(string) | ينشئ كائن حالة النص مع تحديد عائلة الخط. |
| [TextState](textstate/#constructor_3)(Color, double) | ينشئ كائن حالة النص مع تحديد لون المقدمة وحجم الخط. |
| [TextState](textstate/#constructor_6)(string, double) | ينشئ كائن حالة النص مع تحديد عائلة الخط وحجم الخط. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | ينشئ كائن حالة النص مع تحديد عائلة الخط ونمط الخط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | يضبط لون الخلفية للنص. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | يحصل أو يضبط تباعد الأحرف للنص. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | يحصل أو يضبط خاصية CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُعرض النص أعلى من الخطوط الأخرى. في هذه الحالة، يمكن اختيار CoordinateOrigin BaseLine لتحسين عرض النص. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | يحصل أو يضبط خط النص. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | يحصل أو يضبط حجم خط النص. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | يضبط نمط خط النص. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | يحصل أو يضبط لون المقدمة للنص. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | يحصل أو يضبط المحاذاة الأفقية للنص. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | يحصل أو يضبط التحجيم الأفقي للنص. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | يحصل أو يضبط عدم ظهور النص. هذا يعكس أساسًا حالة [`RenderingMode`](./renderingmode/)، باستثناء بعض الحالات الخاصة (مثل القص). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | يحصل أو يضبط تباعد الأسطر للنص. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | يحصل أو يضبط وضعية العرض للنص. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | يحصل أو يضبط الشطب للنص، ممثلًا بواسطة كائن [`TextSegment`](../textsegment/). |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | يحصل أو يضبط لون المقدمة للنص. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | يحصل أو يضبط النص تحت السطر. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | يحصل أو يضبط النص فوق السطر. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | يمكنك وضع هذه العلامة في النص لتحديد الجدولة. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | يحصل أو يضبط التسطير للنص، ممثلًا بواسطة كائن [`TextFragment`](../textfragment/). |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | يحصل أو يضبط تباعد الكلمات للنص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | يطبق الإعدادات من كائن textState آخر. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | يقيس ارتفاع الحرف. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | يقيس السلسلة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | القيمة الافتراضية للجدولة في عرض حرف المسافة للخط الافتراضي. |

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


