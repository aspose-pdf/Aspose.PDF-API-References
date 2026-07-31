---
title: "Kelas ThumbnailDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.ThumbnailDevice. Mewakili perangkat gambar yang menyimpan halaman dokumen pdf ke gambar Thumbnail"
type: docs
weight: 3810
url: /id/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Mewakili perangkat gambar yang menyimpan halaman dokumen pdf ke gambar Thumbnail.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Menginisialisasi instance baru dari kelas `ThumbnailDevice` dengan ukuran default gambar thumbnail (200x200 piksel). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Menginisialisasi instance baru dari kelas `ThumbnailDevice`. |

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
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi gambar thumbnail png dan menyimpannya ke aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

### Lihat Juga

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


