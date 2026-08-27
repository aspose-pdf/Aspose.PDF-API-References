---
title: "Kelas DicomDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.DicomDevice. Mewakili perangkat gambar yang membantu menyimpan pdf Document Page ke dalam format Dicom."
type: docs
weight: 3680
url: /id/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Menginisialisasi instance baru dari kelas `DicomDevice` dengan resolusi default. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan ukuran Page yang diberikan, dengan resolusi default (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan dimensi gambar yang diberikan, dengan resolusi default (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan ukuran Page yang diberikan dan resolusi. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan dimensi gambar yang diberikan dan resolusi. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Mendapatkan tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Mendapatkan lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Mengonversi page menjadi Bitmap. |
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Mengonversi Page menjadi Dicom dan menyimpannya ke aliran keluaran. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

### Lihat Juga

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


