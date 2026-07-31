---
title: "Kelas LoadOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.LoadOptions. Tipe LoadOptions menyimpan tingkat abstraksi pada opsi muat individual"
type: docs
weight: 6260
url: /id/net/aspose.pdf/loadoptions/
---
## LoadOptions class

Tipe LoadOptions memegang tingkat abstraksi pada masing-masing opsi muat

```csharp
public abstract class LoadOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Mendapatkan atau mengatur bendera untuk menonaktifkan semua pembatasan lisensi untuk semua font saat memuat file. Ketika `true`, memungkinkan melakukan operasi dengan font yang dilarang oleh lisensi font tersebut, misalnya memungkinkan menyematkan font ke dalam PDF document meskipun aturan lisensi menonaktifkan penyematan untuk font ini. Secara default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Mewakili format file yang dijelaskan oleh `LoadOptions`. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah tindakan default dan operasi Load berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Load harus berhenti. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


