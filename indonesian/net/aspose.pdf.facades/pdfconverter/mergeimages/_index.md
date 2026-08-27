---
title: "PdfConverter.MergeImages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfConverter method. Menggabungkan daftar aliran gambar menjadi satu aliran gambar. Format output Png/jpg/tiff didukung; jika menggunakan format yang tidak didukung, aliran output akan dienkode sebagai Jpeg secara default."
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

Menggabungkan daftar stream gambar menjadi satu stream gambar. Format output Png/jpg/tiff didukung, jika menggunakan format yang tidak didukung, stream output akan dienkode sebagai Jpeg secara default.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputImagesStreams | List`1 | Daftar aliran gambar yang akan digabungkan. |
| outputImageFormat | ImageFormat | Format output gambar untuk aliran yang digabungkan. |
| mergeMode | ImageMergeMode | Mode penggabungan. Digunakan untuk format Png/Jpg. |
| horizontal | Nullable`1 | Rasio horizontal untuk mengatur lebar kanvas aliran gambar output. Digunakan untuk format Png/Jpg dengan ImageMergeMode.Center saja. |
| vertical | Nullable`1 | Rasio vertikal untuk mengatur tinggi kanvas aliran gambar output. Digunakan untuk format Png/Jpg dengan ImageMergeMode.Center saja. |

### Nilai Kembalian

Aliran gambar dienkode sebagai format gambar output.

### Lihat Juga

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


