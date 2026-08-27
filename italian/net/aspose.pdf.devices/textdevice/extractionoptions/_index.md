---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextDevice. Ottiene o imposta le opzioni di estrazione del testo"
type: docs
weight: 30
url: /it/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Ottiene o imposta le opzioni di estrazione del testo.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Esempi

L'esempio dimostra come estrarre il testo in ordine grezzo.

```csharp
Document doc = new Document(inFile);
string extractedText;

// crea dispositivo di testo
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// converti la pagina e salva il testo nello stream
device.Process(doc.Pages[1], outFile);

// usa il testo estratto
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Vedi anche

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


