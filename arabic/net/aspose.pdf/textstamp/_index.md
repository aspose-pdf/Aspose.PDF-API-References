---
title: TextStamp
second_title: Aspose.PDF لمرجع .NET API
description: يعرض طابعًا نصيًا .
type: docs
weight: 7240
url: /ar/net/aspose.pdf/textstamp/
---
## TextStamp class

يعرض طابعًا نصيًا .

```csharp
public class TextStamp : Stamp
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextStamp](textstamp#constructor)(FormattedText) | يقوم بتهيئة مثيل جديد لملف[`TextStamp`](../textstamp) فئة ذات كائن نص منسق |
| [TextStamp](textstamp#constructor_1)(string) | يقوم بتهيئة مثيل جديد لملف[`TextStamp`](../textstamp) فئة . |
| [TextStamp](textstamp#constructor_2)(string, TextState) | يقوم بتهيئة مثيل جديد لملف[`TextStamp`](../textstamp) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | تعيين أو الحصول على قيمة منطقية تشير إلى أن المحتوى مختوم كخلفية. إذا كانت القيمة صحيحة ، يتم وضع محتوى الختم في الأسفل. بالقيمة غير صحيحة ، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | الحصول على الهامش السفلي للطوابع أو تعيينه. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | تحدد هذه الخاصية كيفية رسم الطابع على الصفحة. إذا تم رسم الختم Draw = true كمشغلات رسوم وإذا كان الرسم = false ، فسيتم رسم الطابع كنص. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | الارتفاع المطلوب للختم على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للطابع على الصفحة. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | يحدد تبرير النص. إذا تم تعيين هذه الخاصية على true ، فسيتم محاذاة كل من الحواف اليمنى واليسرى للنص. القيمة الافتراضية: false . |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | الحصول على الهامش الأيسر للطوابع أو تعيينه. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | أقصى ارتفاع للصف لخيار WordWrap. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | الحصول على أو تعيين قيمة للإشارة إلى عتامة الختم. القيمة من 0.0 إلى 1.0. القيمة الافتراضية هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | الحصول على أو تعيين قيمة للإشارة إلى تعتيم مخطط الختم. القيمة من 0.0 إلى 1.0. القيمة الافتراضية هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | الحصول على قيمة عرض المخطط التفصيلي للطابع أو تعيينها. القيمة الافتراضية هي 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | الحصول على الهامش الأيمن للطوابع أو تعيينه. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | يضبط أو يحصل على تدوير محتوى الطوابع وفقًا[`Rotation`](../rotation) القيم . ملاحظة. هذه الخاصية مخصصة للزوايا المحددة التي تكون مضاعفات 90 درجة (0 ، 90 ، 180 ، 270 درجة) . لتعيين زاوية عشوائية ، استخدم خاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست من مضاعفات 90 ، فإن خاصية Rotate ترجع Rotation. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | الحصول على أو تعيين زاوية تدوير الختم بالدرجات . تسمح هذه الخاصية بتعيين زاوية تدوير عشوائية. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | يحدد تحجيم النص. إذا تم تعيين هذه الخاصية على "صواب" وتم تحديد قيمة العرض ، فسيتم تغيير حجم النص ليلائم العرض المحدد. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | محاذاة النص داخل الختم. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | يحصل على خصائص نص الختم. نرى[`TextState`](./textstate) للحصول على التفاصيل. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | الحصول على الهامش العلوي للطوابع أو تعيينه. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | يحدد أصل الإحداثيات لوضع النص . إذا كان TreatYIndentAsBaseLine = صحيح (افتراضيًا عند Draw = true) ، سيتم التعامل مع قيمة المسافة الفاصلة على أنها سطر أساسي للنص. سطر النسب) للنص . |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | الحصول على أو تعيين قيمة السلسلة التي يتم استخدامها كطابع على الصفحة. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية للطابع على الصفحة. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | العرض المرغوب للختم على الصفحة. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | تعريف التفاف النص. إذا تم تعيين هذه الخاصية على "صواب" وتم تحديد قيمة العرض ، فسيتم تقسيم النص في عدة أسطر ليناسب العرض المحدد. القيمة الافتراضية: false . |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | إحداثيات ختم أفقي ، تبدأ من اليسار. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | إحداثيات الختم العمودي ، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | عامل تكبير الختم. يسمح بقياس الختم . يرجى ملاحظة أن زوجًا من الخصائص ZoomX و ZoomY يسمحان بتعيين عامل التكبير لكل فأس على حدة. يغير إعداد هذه الخاصية كلاً من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفة ، فإن خاصية Zoom تقوم بإرجاع قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | عامل التكبير الأفقي للختم. يسمح بقياس الطوابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | عامل التكبير الرأسي للختم. يسمح بقياس الطوابع عموديًا. |

## طُرق

| اسم | وصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | إرجاع معرف الطابع . |
| override [Put](../../aspose.pdf/textstamp/put)(Page) | يضيف طابعًا نصيًا على الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | تعيين معرف الختم. |

### أنظر أيضا

* class [Stamp](../stamp)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
