---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-egenskap. Hämtar eller ställer in kodningen av extraherad text
type: docs
weight: 20
url: /sv/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding-egenskap

Hämtar eller ställer in kodningen av extraherad text.

```csharp
public Encoding Encoding { get; set; }
```

## Exempel

Exemplet visar hur man representerar extraherad text i UTF-8-kodning.

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

### Se Även

* klass [TextDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* sammansättning [Aspose.PDF](../../../)