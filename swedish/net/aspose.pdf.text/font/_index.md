---
title: "Klass Font"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.Font klass. Representerar teckensnittobjekt"
type: docs
weight: 10690
url: /sv/net/aspose.pdf.text/font/
---
## Font class

Representerar ett teckensnittobjekt.

```csharp
public sealed class Font
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Hämtar BaseFont‑värdet för PDF‑teckensnittobjektet. Även känt som PostScript‑namnet på teckensnittet. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Ibland kan PDF‑teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn. Detta namn är värdet på PDF‑teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap representeras i hexadecimalt format. Om man läser detta namn direkt kan det visas i ett oläsbart format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt regler som är specifika för detta teckensnitt. Denna egenskap returnerar avkodat teckensnittsnamn, så använd den i fall där du stöter på ett oläsbart [`FontName`](./fontname/). Om egenskapen [`FontName`](./fontname/) har ett läsbart format kommer denna egenskap att vara densamma som [`FontName`](./fontname/), så du kan använda denna egenskap i alla fall där du behöver få teckensnittsnamnet i ett läsbart format. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Hämtar teckensnittsnamnet för `Font`‑objektet. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Användbara egenskaper för att finjustera Font-beteende. |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Hämtar indikation på om teckensnittet finns (är installerat) i systemet. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Hämtar eller anger ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserade på IFont kommer automatiskt att bli delmängd och inbäddade. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Hämtar eller anger ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserade på IFont kommer automatiskt att bli delmängd och inbäddade. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Syftet med denna metod är att returnera en felbeskrivning om ett försök att inbädda teckensnittet misslyckades. Om det inte finns några felreturneras en tom sträng. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mäter strängen. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Sparar teckensnittet i strömmen. Observera att teckensnittet sparas i ett intermediat TTF‑format som endast är avsett att användas i en konverterad kopia av det ursprungliga dokumentet. Teckensnittsfilen är inte avsedd att användas utanför det ursprungliga dokumentets sammanhang. |

## Exempel

Exemplet visar hur man söker text på den första sidan och ändrar teckensnittet för den första sökträffen.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Skapa teckensnitt och markera det för inbäddning
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;


// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


