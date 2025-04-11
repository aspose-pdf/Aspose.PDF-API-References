---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-Eigenschaft. Ruft die Kodierung des extrahierten Textes ab oder legt sie fest
type: docs
weight: 20
url: /de/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding-Eigenschaft

Ruft die Kodierung des extrahierten Textes ab oder legt sie fest.

```csharp
public Encoding Encoding { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man extrahierten Text in UTF-8-Kodierung darstellt.

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

### Siehe auch

* Klasse [TextDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)