---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-egenskap. Hämtar eller ställer in alternativ för textutvinning
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions-egenskap

Hämtar eller ställer in alternativ för textutvinning.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Anmärkningar

Möjliggör att definiera textformateringsläge [`TextExtractionOptions`](../../textextractionoptions/) under utvinning. Standardläget är Pure

## Exempel

Exemplet visar hur man ställer in Pure textformateringsläge och utför textutvinning.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### Se Även

* klass [TextExtractionOptions](../../textextractionoptions/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)