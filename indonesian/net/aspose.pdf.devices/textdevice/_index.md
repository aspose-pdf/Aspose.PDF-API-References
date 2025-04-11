---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.TextDevice. Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks
type: docs
weight: 3680
url: /id/net/aspose.pdf.devices/textdevice/
---
## Kelas TextDevice

Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks.

```csharp
public sealed class TextDevice : PageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Menginisialisasi instance baru dari `TextDevice` dengan mode pemformatan teks mentah dan pengkodean teks Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Menginisialisasi instance baru dari `TextDevice` untuk pengkodean yang ditentukan. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Menginisialisasi instance baru dari `TextDevice` dengan opsi ekstraksi teks. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Menginisialisasi instance baru dari `TextDevice` untuk pengkodean yang ditentukan dengan opsi ekstraksi teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Mendapatkan atau menetapkan pengkodean teks yang diekstrak. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Mendapatkan atau menetapkan opsi ekstraksi teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Mengonversi halaman dan menyimpannya sebagai aliran teks. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Catatan

Objek `TextDevice` pada dasarnya digunakan untuk mengekstrak teks dari halaman pdf.

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

* kelas [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)