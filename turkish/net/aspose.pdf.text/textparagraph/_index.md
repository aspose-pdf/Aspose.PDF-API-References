---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph sınıfı. Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder
type: docs
weight: 10990
url: /tr/net/aspose.pdf.text/textparagraph/
---
## TextParagraph sınıfı

Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder.

```csharp
public sealed class TextParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TextParagraph](textparagraph/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | Sonraki satırların girinti değerini alır veya ayarlar. Sıfırdan farklı bir değere ayarlandığında, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | Biçimlendirme seçeneklerini alır veya ayarlar. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | Paragrafın içindeki metin için yatay hizalamayı alır veya ayarlar. |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | Metnin hizalanıp hizalanmadığını belirten değeri alır veya ayarlar. |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | Kenar boşluğunu alır veya ayarlar. |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | Paragrafın konumunu alır veya ayarlar. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | Paragrafın dikdörtgenini alır veya ayarlar. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | Derece cinsinden döndürme açısını alır veya ayarlar. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | Sonraki satırların girinti değerini alır veya ayarlar. Sıfırdan farklı bir değere ayarlandığında, FormattingOptions.SubsequentLinesIndent değerine göre bir avantaj sağlar. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | Paragrafa yerleştirilen metnin dikdörtgenini alır. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | Paragrafın içindeki metin için dikey hizalamayı alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | Metin satırını ekler |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | Metin durumu parametreleri ile metin satırını ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | Metin satırını ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | Metin durumu parametreleri ile metin satırını ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | Metin durumu parametreleri ile metin satırını ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | Metin durumu parametreleri ile metin satırını ekler |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | Metin durumu parametreleri ile metin satırını ekler |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | TextParagraph'ın düzenlemesini başlatır. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | TextParagraph'ın düzenlemesini sonlandırır. |

## Örnekler

Örnek, metin paragrafı nesnesi oluşturmayı ve bunu Pdf sayfasına eklemeyi gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)