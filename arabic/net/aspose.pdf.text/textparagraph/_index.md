---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextParagraph. تمثل فقرات النص ككائن نص متعدد الأسطر
type: docs
weight: 10990
url: /ar/net/aspose.pdf.text/textparagraph/
---
## فئة TextParagraph

تمثل فقرات النص ككائن نص متعدد الأسطر.

```csharp
public sealed class TextParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextParagraph](textparagraph/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | يحصل أو يحدد قيمة إزاحة الأسطر التالية. إذا تم تعيينه على قيمة غير صفرية، فإنه يتمتع بميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | يحصل أو يحدد خيارات التنسيق. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية للنص داخل [`Rectangle`](./rectangle/) الفقرة. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | يحصل أو يحدد ما إذا كان النص مبررًا. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | يحصل أو يحدد الحشو. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | يحصل أو يحدد موضع الفقرة. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | يحصل أو يحدد مستطيل الفقرة. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | يحصل أو يحدد زاوية الدوران بالدرجات. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | يحصل أو يحدد قيمة إزاحة الأسطر التالية. إذا تم تعيينه على قيمة غير صفرية، فإنه يتمتع بميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | يحصل على مستطيل النص الموضوع في الفقرة. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية للنص داخل [`Rectangle`](./rectangle/) الفقرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | يضيف سطر نص |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | يضيف سطر نص مع معلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | يضيف سطر نص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | يضيف سطر نص مع معلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | يضيف سطر نص مع معلمات حالة النص. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | يضيف سطر نص مع معلمات حالة النص |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | يضيف سطر نص مع معلمات حالة النص |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | يبدأ تحرير TextParagraph. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | ينهي تحرير TextParagraph. |

## أمثلة

توضح المثال كيفية إنشاء كائن فقرة نصية وإضافته إلى صفحة PDF.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)