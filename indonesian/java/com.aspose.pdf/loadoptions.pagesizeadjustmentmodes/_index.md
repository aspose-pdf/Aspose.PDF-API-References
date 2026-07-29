---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "PERHATIAN! Fitur telah diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED terdeteksi untuk dokumen contoh. Mewakili mode penggunaan ukuran halaman."
type: docs
weight: 2810
url: /id/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

PERHATIAN! Fitur telah diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll) biasanya memiliki desain mengambang, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten menentukan posisi horizontal atau ukuran yang tidak memungkinkan menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil).

## Fields

| Field | Deskripsi |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Mode ini mendefinisikan perilaku berikut: setelah mendapatkan hasil konversi, dan mendeteksi fakta bahwa sebagian konten telah terpotong, lebar portview diperbesar untuk menyesuaikan konten dan konversi diulang. Mode ini memungkinkan mendapatkan lebih sedikit halaman dalam hasil dalam kasus tersebut tetapi memerlukan rendering berulang (dan oleh karena itu waktu pemrosesan lebih lama). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | Dalam mode ini, halaman hasil akan memiliki ukuran halaman yang diperlukan yang didefinisikan dalam LoadOptions, terlepas apakah konten setelah konversi keluar dari batas halaman atau tidak. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Mode ini mendefinisikan perilaku berikut: setelah mendapatkan hasil konversi, dan mendeteksi fakta bahwa sebagian konten telah terpotong, lebar portview diperbesar untuk menyesuaikan konten dan konversi diulang. Mode ini memungkinkan mendapatkan lebih sedikit halaman dalam hasil dalam kasus tersebut tetapi memerlukan rendering berulang (dan oleh karena itu waktu pemrosesan lebih lama).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

Dalam mode ini, halaman hasil akan memiliki ukuran halaman yang diperlukan yang didefinisikan dalam LoadOptions, terlepas apakah konten setelah konversi keluar dari batas halaman atau tidak.
