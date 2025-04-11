---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextAbsorber. Ottiene o imposta le opzioni di estrazione del testo
type: docs
weight: 30
url: /it/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Proprietà TextAbsorber.ExtractionOptions

Ottiene o imposta le opzioni di estrazione del testo.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Osservazioni

Consente di definire la modalità di formattazione del testo [`TextExtractionOptions`](../../textextractionoptions/) durante l'estrazione. La modalità predefinita è Pure

## Esempi

L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo.

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

### Vedi Anche

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)