---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-Eigenschaft. Ruft die Textextraktionsoptionen ab oder legt sie fest
type: docs
weight: 30
url: /de/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions-Eigenschaft

Ruft die Textextraktionsoptionen ab oder legt sie fest.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Bemerkungen

Ermöglicht die Definition des Textformatierungsmodus [`TextExtractionOptions`](../../textextractionoptions/) während der Extraktion. Der Standardmodus ist Pure

## Beispiele

Das Beispiel zeigt, wie man den Pure-Textformatierungsmodus festlegt und die Textextraktion durchführt.

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

### Siehe auch

* Klasse [TextExtractionOptions](../../textextractionoptions/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)