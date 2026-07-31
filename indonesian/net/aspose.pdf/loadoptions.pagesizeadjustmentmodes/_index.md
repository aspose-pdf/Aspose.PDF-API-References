---
title: "Enum LoadOptions.PageSizeAdjustmentModes"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes. ATTENTION Fitur telah diimplementasikan tetapi belum dipublikasikan ke API publik karena masalah blokir pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format seperti HTML, EPUB, dll biasanya memiliki desain mengambang sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten menentukan posisi horizontal atau ukuran yang tidak memungkinkan menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus ini kita dapat menentukan apa yang harus dilakukan, yaitu ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil."
type: docs
weight: 6280
url: /id/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION! Fitur telah diimplementasikan tetapi belum dipublikasikan ke API publik karena masalah blokir pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengambang, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten menentukan posisi horizontal atau ukuran yang tidak memungkinkan menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus ini kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan dari dokumen PDF hasil).

```csharp
public enum PageSizeAdjustmentModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Dalam mode ini, halaman hasil akan memiliki ukuran halaman yang diperlukan sebagaimana didefinisikan dalam LoadOptions, terlepas apakah konten setelah konversi melampaui batas halaman atau tidak. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Mode ini mendefinisikan perilaku tersebut: setelah memperoleh hasil konversi, dan mendeteksi fakta bahwa sebagian konten terpotong, lebar portview diperbesar untuk menyesuaikan konten dan konversi diulang. Mode ini memungkinkan memperoleh lebih sedikit halaman dalam hasil pada kasus tersebut tetapi memerlukan rendering berulang (dan oleh karena itu waktu pemrosesan lebih lama). |

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


