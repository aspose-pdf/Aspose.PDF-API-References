---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfConverter. Menggabungkan daftar aliran gambar menjadi satu aliran gambar. Format keluaran Png/jpg/tiff didukung jika menggunakan aliran keluaran format yang tidak didukung yang dikodekan sebagai Jpeg secara default
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Metode PdfConverter.MergeImages

Menggabungkan daftar aliran gambar menjadi satu aliran gambar. Format keluaran Png/jpg/tiff didukung, jika menggunakan aliran keluaran format yang tidak didukung yang dikodekan sebagai Jpeg secara default.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputImagesStreams | List`1 | Daftar aliran gambar yang akan digabungkan. |
| outputImageFormat | ImageFormat | Format keluaran gambar untuk aliran yang digabungkan. |
| mergeMode | ImageMergeMode | Mode penggabungan. Digunakan untuk format Png/Jpg. |
| horizontal | Nullable`1 | Rasio horizontal untuk mengatur lebar kanvas untuk aliran gambar keluaran. Digunakan untuk format Png/Jpg dengan ImageMergeMode.Center saja. |
| vertical | Nullable`1 | Rasio vertikal untuk mengatur tinggi kanvas untuk aliran gambar keluaran. Digunakan untuk format Png/Jpg dengan ImageMergeMode.Center saja. |

### Nilai Kembali

Aliran gambar yang dikodekan sebagai format gambar keluaran.

### Lihat Juga

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)