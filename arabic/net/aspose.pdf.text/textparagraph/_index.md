---
title: "الفئة TextParagraph"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TextParagraph. تمثل فقرات النص ككائن نص متعدد الأسطر."
type: docs
weight: 11170
url: /ar/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

يمثل فقرات النص ككائن نص متعدد الأسطر.

```csharp
public sealed class TextParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextParagraph](textparagraph/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | يحصل أو يعيّن قيمة مسافة إزاحة الأسطر اللاحقة. إذا تم تعيينها إلى قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | يحصل أو يعيّن خيارات التنسيق. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن المحاذاة الأفقية للنص داخل [`Rectangle`](./rectangle/) الخاص بالفقرة. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | يحصل أو يعيّن القيمة التي تحدد ما إذا كان النص مبررًا. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | يحصل أو يعيّن الحشو. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | يحصل أو يعيّن موضع الفقرة. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | يحصل أو يعيّن مستطيل الفقرة. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | يحصل أو يعيّن زاوية الدوران بالدرجات. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | يحصل أو يعيّن قيمة مسافة إزاحة الأسطر اللاحقة. إذا تم تعيينها إلى قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | يحصل على مستطيل النص الموضوع داخل الفقرة. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن المحاذاة العمودية للنص داخل [`Rectangle`](./rectangle/) الخاص بالفقرة. |

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
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | ينتهي تحرير TextParagraph. |

## أمثلة

يوضح المثال كيفية إنشاء كائن فقرة نصية وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// إنشاء فقرة نصية
TextParagraph paragraph = new TextParagraph();
           
// تعيين مستطيل الفقرة
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// تعيين خيارات التفاف الكلمات
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// إلحاق سطور النص
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// إلحاق الفقرة بصفحة Pdf باستخدام TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// حفظ مستند Pdf
doc.Save(outFile);
```

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


