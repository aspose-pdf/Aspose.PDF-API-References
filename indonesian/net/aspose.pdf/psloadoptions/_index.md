---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PsLoadOptions. Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf
type: docs
weight: 9730
url: /id/net/aspose.pdf/psloadoptions/
---
## Kelas PsLoadOptions

Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Mendapatkan atau mengatur jalur folder font. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)