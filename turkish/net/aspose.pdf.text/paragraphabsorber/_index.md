---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber sınıfı. Bölümler ve paragraflar gibi sayfa yapı nesnelerinin bir emici nesnesini temsil eder. Metin bölümleri ve paragraflar için arama yapar ve metin koordinat alanında tanımlayan dikdörtgenler ve çokgenler için erişim sağlar. Ayrıca metin segmentleri araması yapar ve yapı öğelerine göre gruplandırılmış TextFragments koleksiyonları aracılığıyla arama sonuçlarına erişim sağlar.
type: docs
weight: 10670
url: /tr/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber sınıfı

Bölümler ve paragraflar gibi sayfa yapı nesnelerinin bir emici nesnesini temsil eder. Metin bölümleri ve paragraflar için arama yapar ve metin koordinat alanında tanımlayan dikdörtgenler ve çokgenler için erişim sağlar. Ayrıca metin segmentleri araması yapar ve yapı öğelerine göre gruplandırılmış !:TextFragments koleksiyonları aracılığıyla arama sonuçlarına erişim sağlar.

```csharp
public class ParagraphAbsorber
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Belgenin veya sayfanın bölümlerini/paragraflarını arayan `ParagraphAbsorber`'ın yeni bir örneğini başlatır. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Belgenin veya sayfanın bölümlerini/paragraflarını arayan `ParagraphAbsorber`'ın yeni bir örneğini başlatır. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Belirtilen parametrelerle belgenin veya sayfanın bölümlerini/paragraflarını arayan `ParagraphAbsorber`'ın yeni bir örneğini başlatır. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Belirtilen parametrelerle belgenin veya sayfanın bölümlerini/paragraflarını arayan `ParagraphAbsorber`'ın yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Bir sonraki bölümün başlangıç metin satırlarının, önceki bölümün son paragrafının devamı olarak kabul edilip edilmeyeceğini belirten değeri alır veya ayarlar. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Emilen [`PageMarkup`](../pagemarkup/) koleksiyonunu alır. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | ParagraphAbsorberOptions'ı alır veya ayarlar. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Yapının daha ince öğeleri için kaç kez ardışık arama yapılacağını belirten değeri alır veya ayarlar. Varsayılan arama derinliği 3'tür. Bu, yatay olarak bölünmüş bölümler (başlıklar, paragraflar vb.) için üç arama ve dikey olarak bölünmüş bölümler (sütunlar) için üç arama anlamına gelir. |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | TextReplaceOptions'ı alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Belirtilen [`Document`](../../aspose.pdf/document/) üzerinde bölümler ve paragraflar için arama yapar. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Belirtilen [`Page`](../../aspose.pdf/page/) üzerinde arama yapar. |

## Açıklamalar

Arama tamamlandığında [`PageMarkups`](./pagemarkups/) koleksiyonu, [`MarkupSection`](../markupsection/) ve [`MarkupParagraph`](../markupparagraph/) koleksiyonlarıyla sayfa yapısını temsil eden [`PageMarkup`](../pagemarkup/) nesnelerini içerecektir. [`TextFragment`](../textfragment/) nesnesi, arama gerçekleşen metne, metin özelliklerine erişim sağlar ve metni düzenlemeye ve metin durumunu (yazı tipi, yazı tipi boyutu, renk vb.) değiştirmeye olanak tanır.

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki her paragrafın ilk metin segmentini bulmayı ve vurgulamayı gösterir.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)