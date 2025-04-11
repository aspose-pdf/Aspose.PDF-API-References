---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Font-egenskap. Hämtar eller ställer in ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att delas upp och inbäddas
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded-egenskap

Hämtar eller ställer in ett värde som indikerar om teckensnittet är inbäddat. Teckensnitt baserat på IFont kommer automatiskt att delas upp och inbäddas

```csharp
public bool IsEmbedded { get; set; }
```

## Exempel

Följande exempel visar hur man hittar ett teckensnitt, markerar det som inbäddat, söker text på dokumentets sida och ersätter textens teckensnitt.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [FontRepository](../../fontrepository/)
* klass [Document](../../../aspose.pdf/document/)
* klass [Font](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)