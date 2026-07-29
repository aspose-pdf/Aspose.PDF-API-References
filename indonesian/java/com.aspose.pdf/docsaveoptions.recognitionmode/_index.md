---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata. Gunakan mode RecognitionMode.Textbox ketika dokumen hasil tidak akan menjadi berat."
type: docs
weight: 1050
url: /id/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata. Gunakan mode RecognitionMode.Textbox ketika dokumen hasil tidak akan banyak diedit lebih lanjut. Kotak teks mudah dimodifikasi ketika tidak banyak yang harus dilakukan. Gunakan mode RecognitionMode.Flow ketika dokumen output memerlukan penyuntingan lebih lanjut. Paragraf dan baris teks dalam mode aliran memungkinkan modifikasi teks yang mudah, tetapi objek pemformatan yang tidak didukung akan terlihat lebih buruk dibandingkan mode RecognitionMode.Textbox.

## Fields

| Field | Deskripsi |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Mode Flow alternatif yang mendukung pengenalan tabel. |
| [Flow](#Flow) | Mode pengenalan penuh, mesin melakukan pengelompokan dan analisis multi-level untuk mengembalikan maksud penulis dokumen asli dan menghasilkan dokumen yang dapat diedit secara maksimal. |
| [Textbox](#Textbox) | Mode ini cepat dan baik untuk mempertahankan tampilan asli file PDF secara maksimal, namun kemampuan edit dokumen hasil dapat terbatas. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Mode Flow alternatif yang mendukung pengenalan tabel.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Mode pengenalan penuh, mesin melakukan pengelompokan dan analisis multi-level untuk mengembalikan maksud penulis dokumen asli dan menghasilkan dokumen yang dapat diedit secara maksimal.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Mode ini cepat dan baik untuk mempertahankan tampilan asli file PDF secara maksimal, namun kemampuan edit dokumen hasil dapat terbatas.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
