---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PageNumberStamp. تمثل ختم رقم الصفحة وتستخدم لترقيم الصفحات
type: docs
weight: 8230
url: /ar/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

تمثل ختم رقم الصفحة وتستخدم لترقيم الصفحات.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Initializes a new instance of the `PageNumberStamp` class. يتم تعيين التنسيق إلى "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Creates PageNumberStamp by formatted text. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Initializes a new instance of the `PageNumberStamp` class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | إذا تم تمكينه، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بحجم: [`Width`](../textstamp/width/) و [`Height`](../textstamp/height/). العرض والارتفاع الافتراضيان مشتقان من مستطيل الصفحة. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | تعيين أو الحصول على قيمة بوليانية تشير إلى أن المحتوى تم ختمه كخلفية. إذا كانت القيمة صحيحة، يتم وضع محتوى الختم في الأسفل. بشكل افتراضي، القيمة خاطئة، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | الحصول على أو تعيين الهامش السفلي للختم. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | تحدد هذه الخاصية كيفية رسم الختم على الصفحة. إذا كانت Draw = true يتم رسم الختم كعمليات رسومية وإذا كانت draw = false يتم رسم الختم كنص. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | حجم الخط الفعلي بعد وضع الختم. (قد يختلف عن حجم الخط الأولي المقدم من خلال المُنشئ إذا كانت خيار 'AutoAdjustFontSizeToFitStampRectangle' مفعلًا.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | قيمة سلسلة لختم أرقام الصفحات. يجب أن تتضمن القيمة الحرف '#' الذي يتم استبداله برقم الصفحة أثناء عملية الختم. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | الارتفاع المرغوب للختم على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للختم على الصفحة. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | تعريف تبرير النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة كلا الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | الحصول على أو تعيين الهامش الأيسر للختم. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | الحد الأقصى لارتفاع الصف لخيار WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | الحصول على أو تعيين الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | نمط الترقيم الذي يستخدمه هذا الختم. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى شفافية الختم. القيمة من 0.0 إلى 1.0. بشكل افتراضي، القيمة هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى شفافية محيط الختم. القيمة من 0.0 إلى 1.0. بشكل افتراضي، القيمة هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | الحصول على أو تعيين قيمة عرض محيط الختم. بشكل افتراضي، القيمة هي 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | الحصول على أو تعيين الخط المستخدم للاستبدال إذا كان خط المستخدم لا يحتوي على الحرف المطلوب. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | الحصول على أو تعيين الهامش الأيمن للختم. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | تعيين أو الحصول على دوران محتوى الختم وفقًا لقيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية، استخدم خاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفًا لـ 90، فإن خاصية Rotate تعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | الحصول على أو تعيين زاوية دوران الختم بالدرجات. تتيح هذه الخاصية تعيين زاوية دوران عشوائية. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | تعريف مقياس النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة العرض، سيتم تغيير حجم النص ليتناسب مع العرض المحدد. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | الحصول على أو تعيين قيمة رقم الصفحة الابتدائية. سيتم ترقيم الصفحات الأخرى بدءًا من هذه القيمة. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | محاذاة النص داخل الختم. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | الحصول على خصائص النص للختم. انظر [`TextState`](../textstamp/textstate/) للتفاصيل. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | الحصول على أو تعيين الهامش العلوي للختم. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | تعريف أصل الإحداثيات لوضع النص. إذا كانت TreatYIndentAsBaseLine = true (الافتراضي عندما تكون Draw = true) سيتم اعتبار قيمة YIndent كخط قاعدة النص. إذا كانت TreatYIndentAsBaseLine = false (الافتراضي عندما تكون Draw = false) سيتم اعتبار قيمة YIndent كخط القاع (خط النزول) للنص. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | الحصول على أو تعيين قيمة سلسلة تستخدم كختم على الصفحة. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية للختم على الصفحة. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | العرض المرغوب للختم على الصفحة. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | الحصول على أو تعيين وضع لف النص لتقديمه. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثيات الختم الأفقية، بدءًا من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثيات الختم الرأسية، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل تكبير الختم. يسمح بتغيير حجم الختم. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور بشكل منفصل. تغيير هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفتين، فإن خاصية Zoom تعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل تكبير الختم الأفقي. يسمح بتغيير حجم الختم أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل تكبير الختم العمودي. يسمح بتغيير حجم الختم عموديًا. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الختم. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | يضيف رقم الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | تعيين معرف الختم. |

### See Also

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)