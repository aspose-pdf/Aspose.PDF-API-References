---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber property. Hämtar eller anger sökalternativ. Alternativen möjliggör sökning med reguljära uttryck."
type: docs
weight: 110
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Hämtar eller anger sökalternativ. Alternativen möjliggör sökning med reguljära uttryck.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Exempel

Exemplet visar hur man utför textsökning med reguljära uttryck.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Gör absorberen så att den söker alla ord som börjar med 'h' och slutar med 'o' med reguljära uttryck.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// vi bör hitta ordet "hello" och ersätta det med "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


