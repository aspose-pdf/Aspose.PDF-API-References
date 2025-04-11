---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-Eigenschaft. Ruft die Textextraktionsoptionen ab oder legt sie fest
type: docs
weight: 30
url: /de/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions-Eigenschaft

Ruft die Textextraktionsoptionen ab oder legt sie fest.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man Text in roher Reihenfolge extrahiert.

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

### Siehe auch

* Klasse [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* Klasse [TextDevice](../)
* Namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../../)