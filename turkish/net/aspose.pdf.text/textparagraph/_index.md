---
title: TextParagraph
second_title: Aspose.PDF for .NET API Referansı
description: Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder.
type: docs
weight: 7150
url: /tr/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

Metin paragraflarını çok satırlı metin nesnesi olarak temsil eder.

```csharp
public sealed class TextParagraph
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TextParagraph](textparagraph)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent) { get; set; } | Sonraki satırların girinti değerini alır veya ayarlar. Sıfırdan farklı bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantajı vardır. |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions) { get; set; } | Biçimlendirme seçeneklerini alır veya ayarlar. |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment) { get; set; } | Paragrafların içindeki metin için yatay hizalamayı alır veya ayarlar[`Rectangle`](./rectangle) . |
| [Justify](../../aspose.pdf.text/textparagraph/justify) { get; set; } | Metnin iki yana yaslı olup olmadığını alır veya ayarlar. |
| [Margin](../../aspose.pdf.text/textparagraph/margin) { get; set; } | Dolguyu alır veya ayarlar. |
| [Position](../../aspose.pdf.text/textparagraph/position) { get; set; } | Paragrafın konumunu alır veya ayarlar. |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle) { get; set; } | Paragrafın dikdörtgenini alır veya ayarlar. |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation) { get; set; } | Dönme açısını derece cinsinden alır veya ayarlar. |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent) { get; set; } | Sonraki satırların girinti değerini alır veya ayarlar. Sıfırdan farklı bir değere ayarlanırsa, FormattingOptions.SubsequentLinesIndent değerine göre bir avantajı vardır. |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle) { get; } | Paragrafa yerleştirilen metnin dikdörtgenini alır. |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment) { get; set; } | Paragrafların içindeki metin için dikey hizalamayı alır veya ayarlar[`Rectangle`](./rectangle) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_3)(string) | Metin satırı ekler |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline)(TextFragment) | Metin durumu parametreleriyle metin satırı ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_6)(string, float) | Metin satırı ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_4)(string, TextState) | Metin durumu parametreleriyle metin satırı ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_1)(TextFragment, TextState) | Metin durumu parametreleriyle metin satırı ekler. |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_5)(string, TextState, float) | Metin durumu parametreleriyle metin satırı ekler |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline#appendline_2)(TextFragment, TextState, float) | Metin durumu parametreleriyle metin satırı ekler |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit)() | TextParagraph'ın düzenlenmesine başlar. |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit)() | TextParagraph'ın düzenlenmesini sonlandırır. |

### Örnekler

Örnek, metin paragraf nesnesinin nasıl oluşturulacağını ve bunun Pdf sayfasına nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// metin paragrafı oluştur
TextParagraph paragraph = new TextParagraph();
           
// paragraf dikdörtgenini ayarla
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// kelime kaydırma seçeneklerini ayarla
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// string satırları ekle
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// Paragrafı TextBuilder ile Pdf sayfasına ekleyin
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// PDF belgesini kaydet
doc.Save(outFile);
```

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->