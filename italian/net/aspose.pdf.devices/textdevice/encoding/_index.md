---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextDevice. Ottiene o imposta la codifica del testo estratto
type: docs
weight: 20
url: /it/net/aspose.pdf.devices/textdevice/encoding/
---
## Proprietà TextDevice.Encoding

Ottiene o imposta la codifica del testo estratto.

```csharp
public Encoding Encoding { get; set; }
```

## Esempi

L'esempio dimostra come rappresentare il testo estratto in codifica UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Vedi Anche

* classe [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)