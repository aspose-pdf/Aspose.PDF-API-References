---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.DicomDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam format Dicom
type: docs
weight: 3560
url: /id/net/aspose.pdf.devices/dicomdevice/
---
## Kelas DicomDevice

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam format Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Menginisialisasi instance baru dari kelas `DicomDevice` dengan resolusi default. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan ukuran halaman yang diberikan, dengan resolusi default (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan dimensi gambar yang diberikan, dengan resolusi default (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan ukuran halaman dan resolusi yang diberikan. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `DicomDevice` dengan dimensi gambar dan resolusi yang diberikan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Mendapatkan atau menetapkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Mendapatkan atau menetapkan mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Mendapatkan tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Mendapatkan atau menetapkan opsi rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Mendapatkan lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi Dicom dan menyimpannya dalam aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

### Lihat Juga

* kelas [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)