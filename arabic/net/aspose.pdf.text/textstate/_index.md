---
title: Class TextState
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextState. تمثل حالة نصية لنص
type: docs
weight: 11070
url: /ar/net/aspose.pdf.text/textstate/
---
## فئة TextState

تمثل حالة نصية لنص

```csharp
public class TextState
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextState](textstate/#constructor)() | ينشئ كائن حالة نصية. |
| [TextState](textstate/#constructor_2)(Color) | ينشئ كائن حالة نصية مع تحديد لون المقدمة. |
| [TextState](textstate/#constructor_1)(double) | ينشئ كائن حالة نصية مع تحديد حجم الخط. |
| [TextState](textstate/#constructor_4)(string) | ينشئ كائن حالة نصية مع تحديد عائلة الخط. |
| [TextState](textstate/#constructor_3)(Color, double) | ينشئ كائن حالة نصية مع تحديد لون المقدمة وحجم الخط. |
| [TextState](textstate/#constructor_6)(string, double) | ينشئ كائن حالة نصية مع تحديد عائلة الخط وحجم الخط. |
| [TextState](textstate/#constructor_5)(string, bool, bool) | ينشئ كائن حالة نصية مع تحديد عائلة الخط وأسلوب الخط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [BackgroundColor](../../aspose.pdf.text/textstate/backgroundcolor/) { get; set; } | يحدد لون خلفية النص. |
| virtual [CharacterSpacing](../../aspose.pdf.text/textstate/characterspacing/) { get; set; } | يحصل أو يحدد تباعد الأحرف للنص. |
| virtual [CoordinateOrigin](../../aspose.pdf.text/textstate/coordinateorigin/) { get; set; } | يحصل أو يحدد نقطة الأصل للنص. إذا كانت نقطة الأصل هي Descender، فإن إحداثي Y للنص يتوافق مع أدنى نقطة في الخط. إذا كانت نقطة الأصل هي BaseLine، فإن إحداثي Y للنص يتوافق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة الانحدار للخط كبيرة جدًا، يمكن أن يتم عرض النص أعلى من خطوط أخرى. في هذه الحالة، يمكن اختيار نقطة الأصل BaseLine لتحسين عرض النص. |
| virtual [Font](../../aspose.pdf.text/textstate/font/) { get; set; } | يحصل أو يحدد خط النص. |
| virtual [FontSize](../../aspose.pdf.text/textstate/fontsize/) { get; set; } | يحصل أو يحدد حجم خط النص. |
| virtual [FontStyle](../../aspose.pdf.text/textstate/fontstyle/) { get; set; } | يحدد أسلوب خط النص. |
| virtual [ForegroundColor](../../aspose.pdf.text/textstate/foregroundcolor/) { get; set; } | يحصل أو يحدد لون المقدمة للنص. |
| virtual [HorizontalAlignment](../../aspose.pdf.text/textstate/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية للنص. |
| virtual [HorizontalScaling](../../aspose.pdf.text/textstate/horizontalscaling/) { get; set; } | يحصل أو يحدد التحجيم الأفقي للنص. |
| virtual [Invisible](../../aspose.pdf.text/textstate/invisible/) { get; set; } | يحصل أو يحدد عدم وضوح النص. هذا يعكس بشكل أساسي حالة [`RenderingMode`](./renderingmode/)، باستثناء بعض الحالات الخاصة (مثل القص). |
| virtual [LineSpacing](../../aspose.pdf.text/textstate/linespacing/) { get; set; } | يحصل أو يحدد تباعد الأسطر للنص. |
| virtual [RenderingMode](../../aspose.pdf.text/textstate/renderingmode/) { get; set; } | يحصل أو يحدد وضع العرض للنص. |
| virtual [StrikeOut](../../aspose.pdf.text/textstate/strikeout/) { get; set; } | يحصل أو يحدد الشطب للنص، ممثلاً بواسطة كائن [`TextSegment`](../textsegment/) |
| virtual [StrokingColor](../../aspose.pdf.text/textstate/strokingcolor/) { get; set; } | يحصل أو يحدد لون المقدمة للنص. |
| virtual [Subscript](../../aspose.pdf.text/textstate/subscript/) { get; set; } | يحصل أو يحدد النص الفرعي للنص. |
| virtual [Superscript](../../aspose.pdf.text/textstate/superscript/) { get; set; } | يحصل أو يحدد النص العلوي للنص. |
| virtual [Underline](../../aspose.pdf.text/textstate/underline/) { get; set; } | يحصل أو يحدد التسطير للنص، ممثلاً بواسطة كائن [`TextFragment`](../textfragment/) |
| virtual [WordSpacing](../../aspose.pdf.text/textstate/wordspacing/) { get; set; } | يحصل أو يحدد تباعد الكلمات للنص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [ApplyChangesFrom](../../aspose.pdf.text/textstate/applychangesfrom/)(TextState) | يطبق الإعدادات من حالة نصية أخرى. |
| [MeasureHeight](../../aspose.pdf.text/textstate/measureheight/)(char) | يقيس ارتفاع الحرف. |
| virtual [MeasureString](../../aspose.pdf.text/textstate/measurestring/)(string) | يقيس السلسلة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | القيمة الافتراضية للتبويب في عرض حرف المسافة للخط الافتراضي. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | يمكنك وضع هذا الوسم في النص للإعلان عن التبويب. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)