---
title: ExtractionOptions
second_title: Aspose.PDF för .NET API Referens
description: Hämtar eller ställer in alternativ för textextraktion.
type: docs
weight: 30
url: /sv/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Hämtar eller ställer in alternativ för textextraktion.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

### Exempel

Exemplet visar hur man extraherar text i råordning.

```csharp
Document doc = new Document(inFile);
string extractedText;

// skapa textenhet
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// konvertera sidan och spara text i strömmen
device.Process(doc.Pages[1], outFile);

// använd den extraherade texten
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Se även

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions)
* class [TextDevice](../../textdevice)
* namnutrymme [Aspose.Pdf.Devices](../../textdevice)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
