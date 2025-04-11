---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Properti TextDevice. Mengambil atau mengatur opsi ekstraksi teks
type: docs
weight: 30
url: /id/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Properti TextDevice.OpsiEkstraksi

Mengambil atau mengatur opsi ekstraksi teks.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dalam urutan mentah.

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

### Lihat Juga

* kelas [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* kelas [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)