---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Enum ini mengenumerasikan mode kemungkinan penyematan file yang direferensikan dalam HTML. Ini memungkinkan mengontrol apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam utama."
type: docs
weight: 2130
url: /id/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Enum ini mengenumerasikan mode kemungkinan penyematan file yang direferensikan dalam HTML. Ini memungkinkan kontrol apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah

## Fields

| Field | Deskripsi |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Memaksa menyematkan semua file yang direferensikan (CSS, Gambar, Font) ke dalam markup HTML yang dihasilkan (yaitu ke dalam HTML itu sendiri). Pendekatan ini menghasilkan satu file HTML, tetapi ukuran total output menjadi lebih besar (karena penggunaan enkoding Base64 pada biner) dan tidak semua peramban (terutama yang lama) dapat memproses biner yang disematkan ke dalam HTML dengan sukses. Namun ini memungkinkan memperoleh HTML yang berisi seluruh hasil, tanpa file tambahan. |
| [EmbedCssOnly](#EmbedCssOnly) | Memaksa memisahkan semua file yang direferensikan kecuali CSS (Gambar dan Font). Artinya CSS akan disematkan ke dalam HTML hasil, dan semua file lain yang direferensikan (Gambar dan Font) akan diproses sebagai bagian eksternal. Ini menghasilkan HTML yang cocok untuk berbagai peramban. |
| [NoEmbedding](#NoEmbedding) | Memaksa memisahkan file yang direferensikan (CSS, Gambar, Font). Pendekatan ini menghasilkan sekumpulan file, tetapi ukuran total output menjadi lebih kecil (karena tidak ada enkoding Base64 pada biner). Pendekatan seperti ini juga menghasilkan HTML yang cocok untuk berbagai peramban. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Memaksa menyematkan semua file yang direferensikan (CSS, Gambar, Font) ke dalam markup HTML yang dihasilkan (yaitu ke dalam HTML itu sendiri). Pendekatan ini menghasilkan satu file HTML, tetapi ukuran total output menjadi lebih besar (karena penggunaan enkoding Base64 pada biner) dan tidak semua peramban (terutama yang lama) dapat memproses biner yang disematkan ke dalam HTML dengan sukses. Namun ini memungkinkan memperoleh HTML yang berisi seluruh hasil, tanpa file tambahan.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Memaksa memisahkan semua file yang direferensikan kecuali CSS (Gambar dan Font). Artinya CSS akan disematkan ke dalam HTML hasil, dan semua file lain yang direferensikan (Gambar dan Font) akan diproses sebagai bagian eksternal. Ini menghasilkan HTML yang cocok untuk berbagai peramban.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Memaksa memisahkan file yang direferensikan (CSS, Gambar, Font). Pendekatan ini menghasilkan sekumpulan file, tetapi ukuran total output menjadi lebih kecil (karena tidak ada enkoding Base64 pada biner). Pendekatan seperti ini juga menghasilkan HTML yang cocok untuk berbagai peramban.
