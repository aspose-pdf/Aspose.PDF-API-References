---
title: "TextBuilder.AppendParagraph"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextBuilder. تُضيف فقرة نصية إلى صفحة الـ Pdf"
type: docs
weight: 20
url: /ar/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

يُضيف فقرة نصية إلى صفحة Pdf.

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textParagraph | TextParagraph | كائن فقرة نصية. |

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

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


