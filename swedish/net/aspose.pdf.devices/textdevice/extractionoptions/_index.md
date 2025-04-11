---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice-egenskap. Hämtar eller ställer in alternativ för textutvinning
type: docs
weight: 30
url: /sv/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions-egenskap

Hämtar eller ställer in alternativ för textutvinning.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Exempel

Exemplet visar hur man extraherar text i rå ordning.

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

### Se Även

* klass [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* klass [TextDevice](../)
* namnrymd [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)