---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.Stamp. Kelas yang merepresentasikan cap
type: docs
weight: 4720
url: /id/net/aspose.pdf.facades/stamp/
---
## Kelas Stamp

Kelas yang merepresentasikan cap.

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
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Mendapatkan atau menetapkan nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Mendapatkan atau menetapkan status latar belakang. Jika true, cap akan ditempatkan sebagai latar belakang halaman yang dicap. Secara default diatur ke false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Mendapatkan atau menetapkan opasitas cap. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Mendapatkan atau menetapkan nomor halaman. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Mendapatkan atau menetapkan array dengan nomor halaman yang akan dipengaruhi oleh cap. Jika Pages = null, semua halaman dokumen akan terpengaruh. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Mendapatkan atau menetapkan kualitas cap gambar dalam persen. Nilai yang valid 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Mendapatkan atau menetapkan rotasi cap dalam derajat. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Mendapatkan atau menetapkan pengidentifikasi cap. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Mengatur gambar yang akan digunakan sebagai cap. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Mengatur gambar sebagai cap. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Mengatur teks sebagai cap. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai cap. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Mengatur file PDF dan nomor halaman yang akan digunakan sebagai cap. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Mengatur status teks dari teks cap. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Mengatur ukuran cap gambar. Gambar akan diskalakan sesuai dengan nilai yang ditentukan. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Mengatur posisi di halaman tempat cap akan ditempatkan. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)