---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Proprietà TextDevice. Ottiene o imposta le opzioni di estrazione del testo
type: docs
weight: 30
url: /it/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Proprietà TextDevice.ExtractionOptions

Ottiene o imposta le opzioni di estrazione del testo.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Esempi

L'esempio dimostra come estrarre il testo in ordine grezzo.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Vedi Anche

* classe [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)