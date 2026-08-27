---
title: "Kelas XImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.XImage kelas. Kelas yang mewakili XObject gambar"
type: docs
weight: 11540
url: /id/net/aspose.pdf/ximage/
---
## XImage class

Kelas yang mewakili X-Object gambar.

```csharp
public sealed class XImage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Jika gambar mengandung transparansi maka mengembalikan true; sebaliknya, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Mendapatkan tipe filter gambar. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Mendapatkan versi gambar dalam skala abu-abu. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Mendapatkan tinggi gambar. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Mendapatkan flag yang menunjukkan apakah gambar harus diperlakukan sebagai mask gambar (lihat 8.9.6, "Masked Images"). Jika flag ini true, nilai BitsPerComponent harus 1 dan Mask serta ColorSpace tidak boleh ditentukan; area yang tidak dimask akan dilukis menggunakan warna non-stroking saat ini. Nilai default: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadata gambar. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Mendapatkan atau mengatur nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen mungkin menjadi tidak benar. Harap gunakan metode XImage.Rename dalam kasus ini. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Mendapatkan lebar gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Menambahkan mask stensil ke XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | Mengembalikan daftar string dengan Teks Alternatif untuk XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Mengembalikan tipe warna gambar. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Mengembalikan nama gambar dalam koleksinya. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Mengambil data gambar mentah dari gambar sumber. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Mengembalikan true jika kedua gambar merujuk ke objek yang sama. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Mengganti nama gambar dan menggantikan semua referensi ke gambar dengan nama baru |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Menyimpan data gambar ke dalam aliran sebagai gambar JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Menyimpan gambar ke dalam aliran dengan format yang diminta. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Menyimpan data gambar ke dalam aliran sebagai gambar JPEG dengan resolusi yang ditentukan. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Menyimpan gambar ke dalam aliran dengan format yang diminta dengan resolusi yang ditentukan. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Mengembalikan aliran gambar asli. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | Menetapkan teks alternatif untuk sebuah XImage pada halaman. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


