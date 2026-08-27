---
title: "TextAbsorber.ExtractionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextAbsorber-egenskap. Hämtar eller anger alternativ för textextraktion."
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Hämtar eller anger alternativ för textutdragning.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Anmärkningar

Tillåter att definiera textformateringsläge [`TextExtractionOptions`](../../textextractionoptions/) under extraktionen. Standardläget är Pure.

## Exempel

Exemplet visar hur man ställer in Pure-textformateringsläge och utför textextraktion.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa ett TextAbsorber-objekt för att extrahera text med formatering
TextAbsorber absorber = new TextAbsorber();

// ställ in pure-textformateringsläge
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// acceptera absorberaren för alla dokumentets sidor
doc.Pages.Accept(absorber);

// hämta den extraherade texten
string extractedText = absorber.Text;
```

### Se även

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


