---
title: "فئة TextFragmentState"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Text.TextFragmentState. تمثل حالة نص لمقطع نصي"
type: docs
weight: 11150
url: /ar/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

يمثل حالة النص لقطعة النص.

```csharp
public sealed class TextFragmentState : TextState
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | يقوم بتهيئة نسخة جديدة من كائن `TextFragmentState` باستخدام كائن [`TextFragment`](../textfragment/) المحدد. لا يتم دعم تهيئة `TextFragmentState`. يتوفر TextFragmentState فقط مع خاصية [`TextState`](../textfragment/textstate/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | يضبط لون خلفية النص، الممثل بكائن [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | يحصل أو يضبط تباعد الأحرف للنص، الممثل بكائن [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | يحصل أو يضبط خاصية CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُعرض النص أعلى من الخطوط الأخرى. في هذه الحالة، يمكن اختيار CoordinateOrigin BaseLine لتحسين عرض النص. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | الحصول أو تعيين ما إذا كان علم رسم حدود مستطيل النص. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | الحصول أو تعيين خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | الحصول أو تعيين حجم خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | تعيين نمط خط النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | الحصول أو تعيين لون المقدمة للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | الحصول أو تعيين خيارات التنسيق. سيكون تطبيق الخيارات فعالًا فقط في سيناريوهات المولد. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | يحصل أو يضبط المحاذاة الأفقية للنص. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | الحصول أو تعيين التحجيم الأفقي للنص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | الحصول أو تعيين عدم ظهور النص. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | يحصل أو يضبط تباعد الأسطر للنص. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | الحصول أو تعيين وضع العرض للنص. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | يحصل أو يعيّن زاوية الدوران بالدرجات. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | الحصول أو تعيين شطب النص، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | الحصول أو تعيين عمليات تلوين الخط في عرض [`TextFragment`](../textfragment/) (تحديد النص، حد المستطيل) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | الحصول أو تعيين النص كمنخفض، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | الحصول أو تعيين النص كمرتفع، الممثل بواسطة كائن [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | الحصول على إيقافات التبويب للنص. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | يمكنك وضع هذه العلامة في النص لتحديد الجدولة. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | يحصل أو يضبط التسطير للنص، ممثلًا بواسطة كائن [`TextFragment`](../textfragment/). |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | يحصل أو يضبط تباعد الكلمات للنص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | يطبق الإعدادات من كائن textState آخر. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | يتحقق مما إذا كان يمكن وضع سلسلة الإدخال داخل المستطيل المحدد. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | يقيس ارتفاع الحرف. (طريقتان) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | يقيس السلسلة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | القيمة الافتراضية للجدولة في عرض حرف المسافة للخط الافتراضي. |

## ملاحظات

يوفر طريقة لتغيير الخصائص التالية للنص: الخط ([`Font`](./font/) الخاصية) حجم الخط ([`FontSize`](./fontsize/) الخاصية) نمط الخط ([`FontStyle`](./fontstyle/) الخاصية) لون المقدمة ([`ForegroundColor`](./foregroundcolor/) الخاصية) لون الخلفية ([`BackgroundColor`](./backgroundcolor/) الخاصية) لاحظ أن تغيير خصائص `TextFragmentState` قد يغيّر مجموعة [`Segments`](../textfragment/segments/) الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان هدفك هو إبقاء مجموعة [`Segments`](../textfragment/segments/) دون تغيير، يرجى تغيير المقاطع الداخلية بشكل فردي.

## أمثلة

يوضح المثال كيفية تغيير لون النص وحجم خط النص باستخدام كائن [`TextState`](../textstate/).

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير لون المقدمة للظهور الأول للنص
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// تغيير حجم الخط للظهور الأول للنص
absorber.TextFragments[1].TextState.FontSize = 15;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


