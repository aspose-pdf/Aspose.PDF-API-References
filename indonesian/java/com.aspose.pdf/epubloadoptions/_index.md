---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen PDF."
type: docs
weight: 1220
url: /id/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Membuat opsi muat default untuk mengonversi file EPUB menjadi dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Membuat opsi muat default untuk mengonversi file EPUB menjadi dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Mendapatkan atau mengatur Css khusus yang diterapkan saat membuka dokumen Epub. |
| [getEngineType](#getEngineType--) | Pilih jenis mesin untuk konversi EPUB ke PDF. Defaultnya adalah EngineType.NEW |
| [getMargin](#getMargin--) | Mendapatkan referensi pada objek yang mewakili informasi margin. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) CSS dari dokumen yang diimpor terkait penggunaan margin. |
| [getPageSize](#getPageSize--) | Mendapatkan ukuran halaman output untuk impor. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | PERHATIAN! Fitur ini telah diimplementasikan tetapi belum tersedia di API publik karena ada masalah penghalang pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengalir, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan sehingga tidak dapat dimasukkan ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Mendapatkan atau mengatur Css khusus yang diterapkan saat membuka dokumen Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Pilih jenis mesin untuk konversi EPUB ke PDF. Defaultnya adalah EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Mendapatkan referensi pada objek yang mewakili informasi margin. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) CSS dari dokumen yang diimpor terkait penggunaan margin. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | PERHATIAN! Fitur ini telah diimplementasikan tetapi belum tersedia di API publik karena ada masalah penghalang pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengalir, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan sehingga tidak dapat dimasukkan ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Membuat opsi muat default untuk mengonversi file EPUB menjadi dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Membuat opsi muat default untuk mengonversi file EPUB menjadi dokumen pdf. Ukuran halaman pdf default - A4 300dpi 2480 X 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Mendapatkan atau mengatur Css khusus yang diterapkan saat membuka dokumen Epub.

**Returns:**
nilai String

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Pilih jenis mesin untuk konversi EPUB ke PDF. Defaultnya adalah EngineType.NEW

**Returns:**
Elemen EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Mendapatkan referensi pada objek yang mewakili informasi margin.

**Returns:**
Objek MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) CSS dari dokumen yang diimpor terkait penggunaan margin.

**Returns:**
Nilai MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Mendapatkan ukuran halaman output untuk impor.

**Returns:**
Objek Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

PERHATIAN! Fitur ini telah diimplementasikan tetapi belum tersedia di API publik karena ada masalah penghalang pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengalir, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan sehingga tidak dapat dimasukkan ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil).

**Returns:**
Nilai PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Mendapatkan atau mengatur Css khusus yang diterapkan saat membuka dokumen Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Pilih jenis mesin untuk konversi EPUB ke PDF. Defaultnya adalah EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Mendapatkan referensi pada objek yang mewakili informasi margin.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Mewakili mode penggunaan area margin - mendefinisikan perlakuan instruksi (jika ada) CSS dari dokumen yang diimpor terkait penggunaan margin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| marginsAreaUsageMode |  | Nilai MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

PERHATIAN! Fitur ini telah diimplementasikan tetapi belum tersedia di API publik karena ada masalah penghalang pada lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll), biasanya memiliki desain mengalir, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten memiliki posisi horizontal atau ukuran yang ditentukan sehingga tidak dapat dimasukkan ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | Nilai PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
