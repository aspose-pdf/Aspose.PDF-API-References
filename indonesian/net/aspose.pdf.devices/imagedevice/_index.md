---
title: "Kelas ImageDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.ImageDevice. Kelas abstrak untuk perangkat gambar."
type: docs
weight: 3730
url: /id/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

Kelas abstrak untuk perangkat gambar.

```csharp
public abstract class ImageDevice : PageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Inisialisasi abstrak untuk turunan `ImageDevice`, mengatur resolusi menjadi 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Menginisialisasi sebuah instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi default (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Inisialisasi abstrak untuk turunan `ImageDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Menginisialisasi sebuah instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi default (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi sebuah instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Menginisialisasi sebuah instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan dan resolusi. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Melakukan beberapa operasi pada page yang diberikan, misalnya mengonversi page menjadi gambar grafis. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

### Lihat Juga

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


