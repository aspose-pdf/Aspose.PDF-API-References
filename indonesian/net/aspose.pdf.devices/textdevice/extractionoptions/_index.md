---
title: "TextDevice.ExtractionOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextDevice. Mendapatkan atau mengatur opsi ekstraksi teks"
type: docs
weight: 30
url: /id/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Mendapatkan atau mengatur opsi ekstraksi teks.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mengekstrak teks dalam urutan mentah.

```csharp
Document doc = new Document(inFile);
string extractedText;

// buat perangkat teks
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// konversi halaman dan simpan teks ke aliran
device.Process(doc.Pages[1], outFile);

// gunakan teks yang diekstrak
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Lihat Juga

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


