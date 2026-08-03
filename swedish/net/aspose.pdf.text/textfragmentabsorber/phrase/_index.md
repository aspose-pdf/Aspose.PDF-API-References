---
title: "TextFragmentAbsorber.Phrase"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber-egenskapen. Hämtar eller anger fras som TextFragmentAbsorber söker i PDF-dokumentet eller på sidan."
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Hämtar eller anger fras som [`TextFragmentAbsorber`](../) söker i PDF-dokumentet eller på sidan.

```csharp
public string Phrase { get; set; }
```

## Exempel

Exemplet visar hur man utför textsökning flera gånger och utför textersättningar.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber-objekt för att hitta alla "hello"-textförekomster.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// sök ett annat ord och ersätt det
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


