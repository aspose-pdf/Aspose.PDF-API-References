---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.XImage. Kelas yang mewakili objek gambar X
type: docs
weight: 11350
url: /id/net/aspose.pdf/ximage/
---
## Kelas XImage

Kelas yang mewakili X-Object gambar.

```csharp
public sealed class XImage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Jika gambar mengandung transparansi maka mengembalikan true; jika tidak, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Mendapatkan jenis filter gambar. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Mendapatkan versi gambar dalam skala abu-abu. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Mendapatkan tinggi gambar. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Mendapatkan sebuah flag yang menunjukkan apakah gambar harus diperlakukan sebagai masker gambar (lihat 8.9.6, "Gambar yang Dimasker"). Jika flag ini true, nilai BitsPerComponent harus 1 dan Mask serta ColorSpace tidak boleh ditentukan; area yang tidak dimasker harus dicat menggunakan warna non-stroking saat ini. Nilai default: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadata dari gambar. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Mendapatkan atau mengatur nama gambar. Harap dicatat bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen mungkin menjadi tidak benar. Harap gunakan metode XImage.Rename dalam kasus ini. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Mendapatkan lebar gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Menambahkan masker stensil ke XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Mengembalikan jenis warna gambar. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Mengembalikan nama gambar dalam koleksinya. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Mengambil data gambar mentah dari gambar sumber. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Mengembalikan true jika kedua gambar merujuk ke objek yang sama. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Mengganti nama gambar dan mengganti semua referensi ke gambar dengan nama baru |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Menyimpan data gambar ke dalam stream sebagai gambar JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Menyimpan gambar ke dalam stream dengan format yang diminta. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Menyimpan data gambar ke dalam stream sebagai gambar JPEG dengan resolusi yang ditentukan. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Menyimpan gambar ke dalam stream dengan format yang diminta dengan resolusi yang ditentukan. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Mengembalikan stream gambar asli. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)