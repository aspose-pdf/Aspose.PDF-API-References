---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Properti TextDevice. Mendapatkan atau mengatur encoding teks yang diekstrak
type: docs
weight: 20
url: /id/net/aspose.pdf.devices/textdevice/encoding/
---
## Properti TextDevice.Encoding

Mendapatkan atau mengatur encoding teks yang diekstrak.

```csharp
public Encoding Encoding { get; set; }
```

## Contoh

Contoh ini menunjukkan cara merepresentasikan teks yang diekstrak dalam encoding UTF-8.

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

### Lihat Juga

* kelas [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)