---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextDevice-egenskap. Hämtar eller anger kodning av extraherad text"
type: docs
weight: 20
url: /sv/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Hämtar eller anger kodning för extraherad text.

```csharp
public Encoding Encoding { get; set; }
```

## Exempel

Exemplet visar hur man representerar extraherad text i UTF-8-kodning.

```csharp
Document doc = new Document(inFile);
string extractedText;

// skapa textenhet
TextDevice device = new TextDevice(Encoding.UTF8);

// konvertera sidan och spara texten till strömmen
device.Process(doc.Pages[1], outFile);

// använd den extraherade texten
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Se även

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


