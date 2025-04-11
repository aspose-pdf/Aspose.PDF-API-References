---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextFragmentState. تمثل حالة نص لجزء نصي
type: docs
weight: 10970
url: /ar/net/aspose.pdf.text/textfragmentstate/
---
## حالة TextFragmentState

تمثل حالة نص لجزء نصي.

```csharp
public sealed class TextFragmentState : TextState
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | يقوم بتهيئة مثيل جديد من كائن `TextFragmentState` مع كائن [`TextFragment`](../textfragment/) المحدد. لا تدعم تهيئة `TextFragmentState`. حالة TextFragmentState متاحة فقط مع خاصية [`TextState`](../textfragment/textstate/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | يحدد لون خلفية النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | يحصل أو يحدد تباعد الأحرف للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | يحصل أو يحدد أصل الإحداثيات للنص. إذا كان أصل الإحداثيات هو Descender، فإن إحداثي Y للنص يتوافق مع أدنى نقطة في الخط. إذا كان أصل الإحداثيات هو BaseLine، فإن إحداثي Y للنص يتوافق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة الانحدار للخط كبيرة جدًا، يمكن أن يتم عرض النص أعلى من خطوط أخرى. في هذه الحالة، يمكن اختيار أصل الإحداثيات BaseLine لتحسين عرض النص. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | يحصل أو يحدد إذا كان علم رسم حدود مستطيل النص. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | يحصل أو يحدد خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | يحصل أو يحدد حجم خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | يحدد نمط خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | يحصل أو يحدد لون المقدمة للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | يحصل أو يحدد خيارات التنسيق. سيكون تعيين الخيارات فعالًا فقط في سيناريوهات المولد. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية للنص. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | يحصل أو يحدد المقياس الأفقي للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | يحصل أو يحدد عدم وضوح النص. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | يحصل أو يحدد تباعد الأسطر للنص. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | يحصل أو يحدد وضع العرض للنص. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | يحصل أو يحدد زاوية الدوران بالدرجات. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | يحصل أو يحدد الشطب للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | يحصل أو يحدد عمليات تلوين الحدود الخاصة بعرض [`TextFragment`](../textfragment/) (نص السكتة الدماغية، حدود المستطيل) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | يحصل أو يحدد النص الفرعي للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | يحصل أو يحدد النص العلوي للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | يحصل على نقاط التوقف للنص. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | يحصل أو يحدد التسطير للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | يحصل أو يحدد تباعد الكلمات للنص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | يطبق الإعدادات من حالة نص أخرى. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | يتحقق مما إذا كان يمكن وضع سلسلة الإدخال داخل المستطيل المحدد. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | يقيس ارتفاع الحرف. (2 طرق) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | يقيس السلسلة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | القيمة الافتراضية للتبويب في عرض حرف المسافة للخط الافتراضي. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | يمكنك وضع هذا الوسم في النص للإعلان عن التبويب. |

## الملاحظات

يوفر وسيلة لتغيير الخصائص التالية للنص: الخط ([`Font`](./font/) الخاص) حجم الخط ([`FontSize`](./fontsize/) الخاص) نمط الخط ([`FontStyle`](./fontstyle/) الخاص) لون المقدمة ([`ForegroundColor`](./foregroundcolor/) الخاص) لون الخلفية ([`BackgroundColor`](./backgroundcolor/) الخاص) لاحظ أن تغيير خصائص `TextFragmentState` قد يغير مجموعة [`Segments`](../textfragment/segments/) الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو دمجها في مقطع واحد. إذا كانت متطلباتك هي ترك مجموعة [`Segments`](../textfragment/segments/) دون تغيير، يرجى تغيير المقاطع الداخلية بشكل فردي.

## الأمثلة

توضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن [`TextState`](../textstate/) .

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)