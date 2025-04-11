---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font klass. Representerar fontobjekt
type: docs
weight: 10510
url: /sv/net/aspose.pdf.text/font/
---
## Font klass

Representerar fontobjekt.

```csharp
public sealed class Font
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Hämtar BaseFont-värdet för PDF-fontobjektet. Också känt som PostScript-namnet på fonten. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Ibland kan PDF-fonter (vanligtvis kinesiska/japanska/koreanska fonter) ha specifika fontnamn. Detta namn är värdet av PDF-fontens egenskap "BaseFont" och ibland kan denna egenskap representeras i hexadecimalt format. Om man läser detta namn direkt kan det representeras i en oläslig form. För att få en läsbar form är det nödvändigt att avkoda fontens namn enligt regler specifika för denna font. Denna egenskap returnerar det avkodade fontnamnet, så använd det för fall när du stöter på ett oläsligt [`FontName`](./fontname/). Om egenskapen [`FontName`](./fontname/) har en läsbar form kommer denna egenskap att vara densamma som [`FontName`](./fontname/), så du kan använda denna egenskap för alla fall när du behöver få fontnamnet i en läsbar form. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Hämtar fontnamnet för `Font`-objektet. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Användbara egenskaper för att justera fontens beteende |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Hämtar indikation på om fonten finns (installerad) i systemet. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om fonten är inbäddad. Font baserad på IFont kommer automatiskt att vara subset och inbäddad |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om fonten är en subset. Font baserad på IFont kommer automatiskt att vara subset och inbäddad |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Målet med denna metod är att returnera en beskrivning av felet om ett försök att bädda in fonten misslyckades. Om det inte finns några fel fall returnerar den en tom sträng. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mäta strängen. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Sparar fonten i strömmen. Observera att fonten sparas i ett mellanformat TTF som är avsett att användas i en konverterad kopia av det ursprungliga dokumentet endast. Fontfilen är inte avsedd att användas utanför det ursprungliga dokumentets sammanhang. |

## Exempel

Exemplet visar hur man söker text på första sidan och ändrar fonten för den första sökförekomsten.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se Även

* klass [TextFragmentAbsorber](../textfragmentabsorber/)
* klass [FontRepository](../fontrepository/)
* klass [Document](../../aspose.pdf/document/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)