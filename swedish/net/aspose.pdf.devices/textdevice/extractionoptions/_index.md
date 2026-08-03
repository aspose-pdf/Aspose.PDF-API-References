---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextDevice-egenskap. Hämtar eller anger alternativ för textutdragning"
type: docs
weight: 30
url: /sv/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Hämtar eller anger alternativ för textutdragning.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Exempel

Exemplet visar hur man extraherar text i rå ordning.

```csharp
Document doc = new Document(inFile);
string extractedText;

// skapa textenhet
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// konvertera sidan och spara texten till strömmen
device.Process(doc.Pages[1], outFile);

// använd den extraherade texten
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Se även

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


