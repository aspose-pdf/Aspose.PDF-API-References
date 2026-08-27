---
title: "TextAbsorber.ExtractionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextAbsorber. Ottiene o imposta le opzioni di estrazione del testo"
type: docs
weight: 30
url: /it/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Ottiene o imposta le opzioni di estrazione del testo.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Osservazioni

Consente di definire la modalità di formattazione del testo [`TextExtractionOptions`](../../textextractionoptions/) durante l'estrazione. La modalità predefinita è Pure

## Esempi

L'esempio dimostra come impostare la modalità di formattazione del testo Pure e eseguire l'estrazione del testo.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre il testo con formattazione
TextAbsorber absorber = new TextAbsorber();

// imposta la modalità di formattazione del testo Pure
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accetta l'assorbitore per tutte le pagine del documento
doc.Pages.Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;
```

### Vedi anche

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


