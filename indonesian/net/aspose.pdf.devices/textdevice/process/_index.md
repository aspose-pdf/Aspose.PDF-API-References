---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Metode TextDevice. Mengonversi halaman dan menyimpannya sebagai aliran teks
type: docs
weight: 40
url: /id/net/aspose.pdf.devices/textdevice/process/
---
## Metode TextDevice.Process

Mengonversi halaman dan menyimpannya sebagai aliran teks.

```csharp
public override void Process(Page page, Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Halaman | Halaman yang akan dikonversi. |
| output | Aliran | Aliran hasil. |

## Contoh

Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)