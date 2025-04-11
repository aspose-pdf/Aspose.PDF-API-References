---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.CgmLoadOptions. Berisi opsi untuk memuat/mengimpor file CGM ke dalam dokumen pdf
type: docs
weight: 3010
url: /id/net/aspose.pdf/cgmloadoptions/
---
## Kelas CgmLoadOptions

Berisi opsi untuk memuat/mengimpor file CGM ke dalam dokumen pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Membuat opsi muat default untuk mengonversi file CGM ke dalam dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Membuat opsi muat dengan !:pageSize yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau menetapkan flag untuk menonaktifkan batasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan untuk melakukan operasi dengan font yang dilarang oleh lisensi font ini, misalnya memungkinkan untuk menyematkan font ke dalam dokumen PDF meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Mendapatkan atau menetapkan ukuran halaman keluaran untuk impor. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan baik Lanjutkan atau Hentikan. Lanjutkan adalah tindakan default dan operasi Muat berlanjut, namun pengguna juga dapat mengembalikan Hentikan di mana kasus operasi Muat harus dihentikan. |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)