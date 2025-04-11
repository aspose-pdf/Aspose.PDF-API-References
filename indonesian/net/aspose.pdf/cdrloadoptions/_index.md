---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.CdrLoadOptions. Kelas ini menggambarkan opsi pemuatan CDR
type: docs
weight: 2960
url: /id/net/aspose.pdf/cdrloadoptions/
---
## Kelas CdrLoadOptions

Kelas ini menggambarkan opsi pemuatan CDR.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Pemuatan berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana operasi Pemuatan harus dihentikan. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)