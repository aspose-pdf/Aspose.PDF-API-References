---
title: "Kelas TextDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.TextDevice. Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks."
type: docs
weight: 3800
url: /id/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks.

```csharp
public sealed class TextDevice : PageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Menginisialisasi instance baru dari `TextDevice` dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Menginisialisasi instance baru dari `TextDevice` untuk enkoding yang ditentukan. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Menginisialisasi instance baru dari `TextDevice` dengan opsi ekstraksi teks. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Menginisialisasi instance baru dari `TextDevice` untuk enkoding yang ditentukan dengan opsi ekstraksi teks. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Mendapatkan atau mengatur enkoding teks yang diekstrak. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Mendapatkan atau mengatur opsi ekstraksi teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Konversi halaman dan simpan sebagai aliran teks. |
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

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


