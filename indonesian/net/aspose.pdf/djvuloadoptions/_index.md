---
title: Class DjvuLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.DjvuLoadOptions. Kelas ini menggambarkan opsi pemuatan DJVU
type: docs
weight: 3740
url: /id/net/aspose.pdf/djvuloadoptions/
---
## Kelas DjvuLoadOptions

Kelas ini menggambarkan opsi pemuatan DJVU.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Pemuatan berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Pemuatan harus dihentikan. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)