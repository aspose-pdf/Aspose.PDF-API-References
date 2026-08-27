---
title: "Kelas Stamp"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Facades.Stamp. Kelas yang mewakili stempel"
type: docs
weight: 4840
url: /id/net/aspose.pdf.facades/stamp/
---
## Stamp class

Kelas yang mewakili stempel.

```csharp
public sealed class Stamp
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Stamp](stamp/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Mendapatkan atau mengatur nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Mendapatkan atau mengatur status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang distempel. Secara default diatur ke false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas stempel. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Mendapatkan atau mengatur nomor halaman. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Mendapatkan atau mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. Jika Pages = null, semua halaman dokumen akan dipengaruhi. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Mendapatkan atau mengatur kualitas stempel gambar dalam persen. Nilai yang valid 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Mendapatkan atau mengatur rotasi stempel dalam derajat. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi stempel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Mengatur gambar yang akan digunakan sebagai stempel. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Mengatur gambar sebagai stempel. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Mengatur teks sebagai stempel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Mengatur keadaan teks dari teks stempel. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Mengatur ukuran stempel gambar. Gambar akan diubah skala sesuai nilai yang ditentukan. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Mengatur posisi pada halaman tempat stempel akan ditempatkan. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


