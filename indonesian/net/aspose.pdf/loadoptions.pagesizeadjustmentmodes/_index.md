---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes. PERHATIAN Fitur ini telah diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED yang terungkap untuk dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format seperti HTML EPUB dll biasanya memiliki desain mengambang sehingga memungkinkan untuk menyesuaikan ukuran halaman yang diperlukan. Tetapi terkadang konten memiliki posisi horizontal atau ukuran tertentu yang tidak memungkinkan untuk menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus seperti itu, kita dapat mendefinisikan apa yang harus dilakukan dalam kasus ini, yaitu ketika ukuran konten tidak sesuai dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil.
type: docs
weight: 6140
url: /id/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## Enumerasi LoadOptions.PageSizeAdjustmentModes

PERHATIAN! Fitur ini telah diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED yang terungkap untuk dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB dll), biasanya memiliki desain mengambang, sehingga memungkinkan untuk menyesuaikan ukuran halaman yang diperlukan. Tetapi terkadang konten memiliki posisi horizontal atau ukuran tertentu yang tidak memungkinkan untuk menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus seperti itu, kita dapat mendefinisikan apa yang harus dilakukan dalam kasus ini (yaitu ketika ukuran konten tidak sesuai dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil).

```csharp
public enum PageSizeAdjustmentModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Dalam mode ini, halaman hasil akan memiliki ukuran halaman yang diperlukan yang ditentukan dalam LoadOptions, tidak peduli apakah konten setelah konversi keluar dari batas halaman atau tidak. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Mode ini mendefinisikan perilaku seperti ini: setelah mendapatkan hasil konversi, dan mendeteksi fakta bahwa beberapa konten telah terpotong, lebar portview diperbesar untuk menyesuaikan konten dan konversi diulang. Mode ini memungkinkan mendapatkan lebih sedikit halaman dalam hasil dalam kasus seperti itu tetapi memerlukan rendering ulang (dan oleh karena itu lebih banyak waktu pemrosesan). |

### Lihat Juga

* kelas [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)