---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.SvgLoadOptions. Mewakili opsi untuk memuat/mengimpor file SVG ke dalam dokumen pdf
type: docs
weight: 10210
url: /id/net/aspose.pdf/svgloadoptions/
---
## Kelas SvgLoadOptions

Mewakili opsi untuk memuat/mengimpor file SVG ke dalam dokumen pdf.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Sesuaikan ukuran halaman pdf dengan ukuran svg |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Mendapatkan atau mengatur informasi halaman yang harus diterapkan selama pemuatan dokumen. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Memungkinkan memilih mesin konversi yang akan digunakan selama konversi. Saat ini mesin baru berada dalam tahap B-testing, jadi nilai ini secara default diatur ke ConversionEngines.LegacyEngine |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)