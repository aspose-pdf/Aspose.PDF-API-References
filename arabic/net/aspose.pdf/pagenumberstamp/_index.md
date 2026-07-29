---
title: "الفئة PageNumberStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PageNumberStamp. تمثل ختم رقم الصفحة وتُستخدم لترقيم الصفحات"
type: docs
weight: 8370
url: /ar/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

يمثل ختم رقم الصفحة ويُستخدم لترقيم الصفحات.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `PageNumberStamp`. تم تعيين التنسيق إلى "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | ينشئ PageNumberStamp باستخدام نص مُنسق. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | يُنشئ مثيلاً جديدًا للفئة `PageNumberStamp`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1؛ |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | إذا تم التفعيل، سيتم تعديل حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بالحجم: [`Width`](../textstamp/width/) و[`Height`](../textstamp/height/). العرض والارتفاع الافتراضيان مستمدان من مستطيل الصفحة. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يضبط أو يحصل على قيمة bool تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، تكون القيمة false، ويتم وضع محتوى الطابع في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يضبط الهامش السفلي للطابع. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | تحدد هذه الخاصية كيفية رسم الختم على الصفحة. إذا كان Draw = true يتم رسم الختم كعوامل رسومية وإذا كان draw = false يتم رسم الختم كنص. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | حجم الخط الفعلي بعد وضع الختم. (قد يختلف عن حجم الخط الأولي المقدم عبر المُنشئ إذا تم تمكين خيار 'AutoAdjustFontSizeToFitStampRectangle'.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | قيمة سلسلة لتخطيط أرقام الصفحات. يجب أن تتضمن القيمة الحرف '#' الذي يُستبدل برقم الصفحة أثناء عملية التخطيط. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | الارتفاع المطلوب للطابع على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع الأفقية على الصفحة. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | يحدد محاذاة النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يضبط الهامش الأيسر للطابع. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | الحد الأقصى لارتفاع الصف لخيار WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | يحصل أو يعيّن الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | نمط الترقيم المستخدم في هذا الختم. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يضبط قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | يحصل أو يضبط الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يضبط الهامش الأيمن للطابع. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يضبط أو يحصل على دوران محتوى الطابع وفق قيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفًا للـ 90 فإن خاصية Rotate تُعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يضبط زاوية دوران الطابع بالدرجات. تسمح هذه الخاصية بتعيين زاوية دوران عشوائية. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | يحدد مقياس النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيُقاس النص ليتناسب مع العرض المحدد. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | يحصل أو يعيّن قيمة رقم الصفحة الابتدائية. سيتم ترقيم الصفحات الأخرى بدءًا من هذه القيمة. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | محاذاة النص داخل الختم. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | يحصل على خصائص النص للختم. راجع [`TextState`](../textstamp/textstate/) للتفاصيل. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يضبط الهامش العلوي للطابع. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | يحدد أصل الإحداثيات لوضع النص. إذا كان TreatYIndentAsBaseLine = true (الإعداد الافتراضي عندما Draw = true) فسيتم اعتبار قيمة YIndent كخط أساس النص. إذا كان TreatYIndentAsBaseLine = false (الإعداد الافتراضي عندما Draw = false) فسيتم اعتبار قيمة YIndent كالقاع (خط النزول) للنص. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | يحصل أو يضبط قيمة السلسلة التي تُستخدم كختم على الصفحة. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع العمودية على الصفحة. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | العرض المطلوب للطابع على الصفحة. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | يحصل أو يضبط وضع التفاف الكلمات لعرض النص. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثي الطابع الأفقي، يبدأ من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثي الطابع العمودي، يبدأ من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور على حدة. تغيير هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفة فإن خاصية Zoom تُعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير العمودي للطابع. يسمح بتكبير الطابع عموديًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الطابع. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | يضيف رقم الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يضبط معرف الطابع. |

### انظر أيضًا

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


