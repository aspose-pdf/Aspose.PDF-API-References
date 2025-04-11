---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.ImageDevice. Kelas abstrak untuk perangkat gambar
type: docs
weight: 3610
url: /id/net/aspose.pdf.devices/imagedevice/
---
## Kelas ImageDevice

Kelas abstrak untuk perangkat gambar.

```csharp
public abstract class ImageDevice : PageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Inisialisasi abstrak untuk keturunan `ImageDevice`, mengatur resolusi ke 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi default (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Inisialisasi abstrak untuk keturunan `ImageDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi default (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Mengambil atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Mengambil atau mengatur mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Mengambil tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Mengambil atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Mengambil resolusi gambar. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Mengambil lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Melakukan beberapa operasi pada halaman yang diberikan, misalnya mengonversi halaman menjadi gambar grafis. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

### Lihat Juga

* kelas [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)