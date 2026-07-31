---
title: "TextDevice.Process"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode TextDevice. Mengonversi halaman dan menyimpannya sebagai aliran teks"
type: docs
weight: 40
url: /id/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Konversi halaman dan simpan sebagai aliran teks.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Halaman | Halaman yang akan dikonversi. |
| output | Stream | Aliran hasil. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // buat perangkat teks
    TextDevice device = new TextDevice();

    // konversi halaman dan simpan teks ke aliran
    device.Process(doc.Pages[1], ms);

    // gunakan teks yang diekstrak
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Lihat Juga

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


