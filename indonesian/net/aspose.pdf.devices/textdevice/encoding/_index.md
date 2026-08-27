---
title: "TextDevice.Encoding"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti TextDevice. Mendapatkan atau mengatur enkoding teks yang diekstrak"
type: docs
weight: 20
url: /id/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Mendapatkan atau mengatur enkoding teks yang diekstrak.

```csharp
public Encoding Encoding { get; set; }
```

## Contoh

Contoh ini menunjukkan cara merepresentasikan teks yang diekstrak dalam enkoding UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// buat perangkat teks
TextDevice device = new TextDevice(Encoding.UTF8);

// konversi halaman dan simpan teks ke aliran
device.Process(doc.Pages[1], outFile);

// gunakan teks yang diekstrak
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Lihat Juga

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


