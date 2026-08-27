---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Font egenskap. Hämtar eller anger ett värde som indikerar om teckensnittet är inbäddat. Font baserad på IFont kommer automatiskt att bli delmängd och inbäddad"
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

Hämtar eller anger ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserade på IFont kommer automatiskt att bli delmängd och inbäddade.

```csharp
public bool IsEmbedded { get; set; }
```

## Exempel

Följande exempel visar hur man hittar ett teckensnitt, markerar det som inbäddat, söker text på dokumentets sida och ersätter textens teckensnitt.

```csharp
// Skapa teckensnitt och markera det för inbäddning
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// skapa TextFragmentAbsorber-objekt för att hitta alla "hello world"-textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].TextState.Font = font;

// spara dokumentet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


