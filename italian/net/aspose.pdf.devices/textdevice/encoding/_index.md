---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextDevice. Ottiene o imposta la codifica del testo estratto"
type: docs
weight: 20
url: /it/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Ottiene o imposta la codifica del testo estratto.

```csharp
public Encoding Encoding { get; set; }
```

## Esempi

L'esempio dimostra come rappresentare il testo estratto nella codifica UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// crea dispositivo di testo
TextDevice device = new TextDevice(Encoding.UTF8);

// converti la pagina e salva il testo nello stream
device.Process(doc.Pages[1], outFile);

// usa il testo estratto
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Vedi anche

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


