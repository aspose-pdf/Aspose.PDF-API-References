---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Ketika file PDF (yang biasanya memiliki tata letak tetap) sedang dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk memulihkan dokumen asli."
type: docs
weight: 1250
url: /id/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Ketika file PDF (yang biasanya memiliki tata letak tetap) dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan hasil dalam tata letak aliran. Properti ini menyesuaikan konversi tersebut untuk metode pengenalan konten yang diinginkan.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Fixed](#Fixed) | Mode ini cepat dan baik untuk mempertahankan tampilan asli halaman secara maksimal, tetapi sayangnya banyak pembaca EPUB tidak mendukung XHTML dengan tata letak tetap |
| [Flow](#Flow) | Mode pengenalan penuh, mesin berusaha melakukan pengelompokan dan analisis multi-tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan XHTML dalam tata letak aliran. |
| [PdfFlow](#PdfFlow) | Gagasan utama konversi ini didasarkan pada penyimpanan urutan "natural" konten yang terbentuk selama pemrosesan dokumen PDF. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Mode ini cepat dan baik untuk mempertahankan tampilan asli halaman secara maksimal, tetapi sayangnya banyak pembaca EPUB tidak mendukung XHTML dengan tata letak tetap

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Mode pengenalan penuh, mesin berusaha melakukan pengelompokan dan analisis multi-tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan XHTML dalam tata letak aliran.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

Gagasan utama konversi ini didasarkan pada penyimpanan urutan "natural" konten yang terbentuk selama pemrosesan dokumen PDF.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
