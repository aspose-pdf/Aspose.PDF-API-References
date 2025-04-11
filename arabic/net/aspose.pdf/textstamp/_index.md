---
title: Class TextStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TextStamp class. يمثل ختم نصي
type: docs
weight: 11080
url: /ar/net/aspose.pdf/textstamp/
---
## TextStamp class

يمثل ختم نصي.

```csharp
public class TextStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [TextStamp](textstamp/#constructor)(FormattedText) | يقوم بتهيئة مثيل جديد من فئة `TextStamp` مع كائن formattedText |
| [TextStamp](textstamp/#constructor_1)(string) | يقوم بتهيئة مثيل جديد من فئة `TextStamp`. |
| [TextStamp](textstamp/#constructor_2)(string, TextState) | يقوم بتهيئة مثيل جديد من فئة `TextStamp`. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | يضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | إذا تم تمكينه، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بحجم: [`Width`](./width/) و [`Height`](./height/). العرض والارتفاع الافتراضيان مشتقان من مستطيل الصفحة. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يحدد أو يحصل على قيمة بوليانية تشير إلى أن المحتوى تم ختمه كخلفية. إذا كانت القيمة صحيحة، يتم وضع محتوى الختم في الأسفل. بشكل افتراضي، القيمة خاطئة، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يضبط الهامش السفلي للختم. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | تحدد هذه الخاصية كيفية رسم الختم على الصفحة. إذا كانت Draw = true يتم رسم الختم كعوامل رسومية وإذا كانت draw = false يتم رسم الختم كنص. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | حجم الخط الفعلي بعد وضع الختم. (قد يختلف عن حجم الخط الأولي المقدم من خلال المُنشئ إذا كانت خيار 'AutoAdjustFontSizeToFitStampRectangle' مفعلًا.) |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | الارتفاع المرغوب للختم على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يضبط المحاذاة الأفقية للختم على الصفحة. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | يحدد تبرير النص. إذا تم تعيين هذه الخاصية على true، يتم محاذاة كلا الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يضبط الهامش الأيسر للختم. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | الحد الأقصى لارتفاع الصف لخيار WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | يحصل أو يضبط الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يضبط قيمة تشير إلى شفافية الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، القيمة هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يضبط قيمة تشير إلى شفافية محيط الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، القيمة هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يضبط قيمة عرض محيط الختم. بشكل افتراضي، القيمة هي 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | يحصل أو يضبط الخط المستخدم للاستبدال إذا كان خط المستخدم لا يحتوي على الحرف المطلوب. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يضبط الهامش الأيمن للختم. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يحدد أو يحصل على دوران محتوى الختم وفقًا لقيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية، استخدم خاصية RotateAngle. إذا كانت الزاوية المحددة بواسطة ArbitraryAngle ليست مضاعفًا لـ 90، فإن خاصية Rotate تعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يضبط زاوية دوران الختم بالدرجات. تسمح هذه الخاصية بتعيين زاوية دوران عشوائية. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | يحدد مقياس النص. إذا تم تعيين هذه الخاصية على true وتم تحديد قيمة العرض، سيتم تغيير حجم النص ليتناسب مع العرض المحدد. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | محاذاة النص داخل الختم. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | يحصل على خصائص النص للختم. انظر [`TextState`](./textstate/) للتفاصيل. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يضبط الهامش العلوي للختم. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | يحدد أصل الإحداثيات لوضع النص. إذا كانت TreatYIndentAsBaseLine = true (الافتراضي عندما تكون Draw = true) ستُعتبر قيمة YIndent كخط قاعدة النص. إذا كانت TreatYIndentAsBaseLine = false (الافتراضي عندما تكون Draw = false) ستُعتبر قيمة YIndent كخط القاع (خط النزول) للنص. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | يحصل أو يضبط قيمة سلسلة تُستخدم كختم على الصفحة. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يضبط المحاذاة الرأسية للختم على الصفحة. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | العرض المرغوب للختم على الصفحة. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | يحصل أو يضبط وضع لف الكلمات لتقديم النص. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثيات الختم الأفقية، بدءًا من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثيات الختم الرأسية، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل تكبير الختم. يسمح بتغيير حجم الختم. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور بشكل منفصل. تغيير هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفتين، فإن خاصية Zoom تعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل تكبير الختم الأفقي. يسمح بتغيير حجم الختم أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل تكبير الختم العمودي. يسمح بتغيير حجم الختم عموديًا. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الختم. |
| override [Put](../../aspose.pdf/textstamp/put/)(Page) | يضيف ختم نصي على الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يحدد معرف الختم. |

## Other Members

| Name | Description |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | الإجراء الذي يجب اتخاذه إذا لم يحتوي الخط على الحرف المطلوب. |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)