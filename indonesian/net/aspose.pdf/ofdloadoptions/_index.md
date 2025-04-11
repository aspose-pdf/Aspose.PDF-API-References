---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.OfdLoadOptions. Opsi pemuatan untuk format OFD
type: docs
weight: 7060
url: /id/net/aspose.pdf/ofdloadoptions/
---
## Kelas OfdLoadOptions

Opsi pemuatan untuk format OFD.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Pemuatan berlanjut, namun pengguna juga dapat mengembalikan Menghentikan di mana kasus operasi Pemuatan harus dihentikan. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)