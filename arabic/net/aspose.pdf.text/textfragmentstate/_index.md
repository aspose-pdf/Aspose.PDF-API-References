---
title: TextFragmentState
second_title: Aspose.PDF لمرجع .NET API
description: يمثل حالة نصية لجزء نصي.
type: docs
weight: 7130
url: /ar/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

يمثل حالة نصية لجزء نصي.

```csharp
public sealed class TextFragmentState : TextState
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | تهيئة مثيل جديد لملف[`TextFragmentState`](../textfragmentstate) كائن مع المحدد[`TextFragment`](../textfragment) الكائن . هذا[`TextFragmentState`](../textfragmentstate) التهيئة غير مدعومة. TextFragmentState متاح فقط مع[`TextState`](../textfragment/textstate) الملكية . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | تعيين لون خلفية النص ، الذي يمثله ملف[`TextFragment`](../textfragment) كائن |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | الحصول على تباعد الأحرف في النص أو تعيينه ، والذي يمثله ملف[`TextFragment`](../textfragment) الكائن . |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | يتم الحصول عليه أو تعيينه في حالة رسم علم حدود مستطيل النص. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | الحصول على أو تعيين خط النص ، الذي يمثله ملف[`TextFragment`](../textfragment) كائن |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | الحصول على أو تحديد حجم خط النص الذي يمثله ملف[`TextFragment`](../textfragment) كائن |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | تعيين نمط خط النص ، الذي يمثله ملف[`TextFragment`](../textfragment) كائن |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | الحصول على أو تعيين لون المقدمة للنص الذي يمثله ملف[`TextFragment`](../textfragment) كائن |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | الحصول على خيارات التنسيق أو تعيينها . سيكون إعداد الخيارات فعالاً في سيناريوهات المولد فقط. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | الحصول على محاذاة أفقية للنص أو تعيينها. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | الحصول على أو تعيين القياس الأفقي للنص ، الذي يمثله ملف[`TextFragment`](../textfragment) الكائن . |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | الحصول على إخفاء النص أو تعيينه. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | الحصول على تباعد الأسطر في النص أو تعيينه. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | الحصول على أو تعيين وضع عرض النص. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | الحصول على أو تعيين زاوية الدوران بالدرجات . |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | تعيين شطب للنص ، يمثله ملف[`TextFragment`](../textfragment) كائن |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | الحصول على أو تعيين عمليات ضغط الألوان لـ[`TextFragment`](../textfragment) التقديم (نص الشطب ، حد المستطيل) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | الحصول على أو تعيين خط منخفض من النص ، ويمثله ملف[`TextFragment`](../textfragment) الكائن . |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | الحصول على النص المرتفع أو تعيينه بواسطة[`TextFragment`](../textfragment) الكائن . |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | يحصل على علامات الجدولة للنص. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | للحصول على تسطير أو تعيين للنص الذي يمثله[`TextFragment`](../textfragment) كائن |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | الحصول على أو تعيين تباعد الكلمات في النص. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | يطبق إعدادات من حالة نصية أخرى. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | يقيس السلسلة . |

## مجالات

| اسم | وصف |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | القيمة الافتراضية للجدولة بعرض حرف المسافة للخط الافتراضي. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | يمكنك وضع هذه العلامة في النص لإعلان الجدولة. |

### ملاحظات

يوفر طريقة لتغيير الخصائص التالية للنص: font ([`Font`](./font) الخاصية) حجم الخط ([`FontSize`](./fontsize) الخاصية) نمط الخط ([`FontStyle`](./fontstyle) الخاصية) لون المقدمة ([`ForegroundColor`](./foregroundcolor) الخاصية) لون الخلفية ([`BackgroundColor`](./backgroundcolor) property) لاحظ أن التغيير[`TextFragmentState`](../textfragmentstate) قد تتغير الخصائص الداخلية[`Segments`](../textfragment/segments) لأن TextFragment عبارة عن كائن مجمع وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان مطلبك هو ترك[`Segments`](../textfragment/segments) المجموعة دون تغيير ، يرجى تغيير الأجزاء الداخلية بشكل فردي.

### أمثلة

يوضح المثال كيفية تغيير لون النص وحجم خط النص باستخدام[`TextState`](../textstate) الكائن .

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير لون المقدمة عند ظهور النص الأول
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// تغيير حجم الخط عند ظهور النص الأول
absorber.TextFragments[1].TextState.FontSize = 15;

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
