---
title: TextParagraph
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فقرات نصية ككائن نص متعدد الأسطر.
type: docs
weight: 7150
url: /ar/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

يمثل فقرات نصية ككائن نص متعدد الأسطر.

```csharp
public sealed class TextParagraph
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextParagraph](textparagraph)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent) { get; set; } | الحصول على قيمة المسافة البادئة للأسطر اللاحقة أو تعيينها . إذا تم تعيينها على قيمة غير صفرية ، فإنها تتمتع بميزة على خيارات التنسيق. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions) { get; set; } | الحصول على خيارات التنسيق أو تعيينها . |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للنص داخل Paragrph's[`Rectangle`](./rectangle) . |
| [Justify](../../aspose.pdf.text/textparagraph/justify) { get; set; } | الحصول على القيمة أو تعيينها سواء كان النص مضبوطًا. |
| [Margin](../../aspose.pdf.text/textparagraph/margin) { get; set; } | الحصول على المساحة المتروكة أو تعيينها. |
| [Position](../../aspose.pdf.text/textparagraph/position) { get; set; } | الحصول على موضع الفقرة أو تحديده . |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle) { get; set; } | الحصول على مستطيل الفقرة أو تعيينه . |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation) { get; set; } | الحصول على أو تعيين زاوية الدوران بالدرجات . |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent) { get; set; } | الحصول على قيمة المسافة البادئة للأسطر اللاحقة أو تعيينها . إذا تم تعيينها على قيمة غير صفرية ، فإنها تتمتع بميزة على خيارات التنسيق. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle) { get; } | يحصل على مستطيل من النص موضوع في الفقرة. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية للنص داخل Paragrph's[`Rectangle`](./rectangle) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_3)(string) | إلحاق سطر نصي |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline)(TextFragment) | إلحاق سطر نص بمعلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_6)(string, float) | إلحاق سطر نص . |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_4)(string, TextState) | إلحاق سطر نص بمعلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_1)(TextFragment, TextState) | إلحاق سطر نص بمعلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_5)(string, TextState, float) | إلحاق سطر نص بمعلمات حالة النص |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_2)(TextFragment, TextState, float) | إلحاق سطر نص بمعلمات حالة النص |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit)() | يبدأ تحرير TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit)() | إنهاء تحرير TextParagraph. |

### أمثلة

يوضح المثال كيفية إنشاء كائن فقرة نصية وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// إنشاء فقرة نصية
TextParagraph paragraph = new TextParagraph();
           
// اضبط مستطيل الفقرة
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// تعيين خيارات التفاف الكلمات
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// إلحاق خطوط السلسلة
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// إلحاق الفقرة بصفحة Pdf باستخدام TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// حفظ مستند PDF
doc.Save(outFile);
```

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->