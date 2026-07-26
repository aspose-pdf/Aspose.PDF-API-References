---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mode perenderan teks, Tmode, menentukan apakah menampilkan teks akan menyebabkan kontur glif digambar, diisi, digunakan sebagai batas pemotongan, atau kombinasi dari ketiganya."
type: docs
weight: 5240
url: /id/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

Mode perenderan teks, Tmode, menentukan apakah menampilkan teks akan menyebabkan kontur glif digambar, diisi, digunakan sebagai batas pemotongan, atau kombinasi dari ketiganya.

## Fields

| Field | Deskripsi |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Tambahkan teks ke jalur untuk pemotongan. |
| [FillText](#FillText) | Isi teks. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Isi teks dan tambahkan ke jalur untuk pemotongan (lihat 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Isi, lalu beri gores pada teks. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Isi, lalu beri gores pada teks dan tambahkan ke jalur untuk pemotongan. |
| [Invisible](#Invisible) | Tidak mengisi maupun memberi gores pada teks (tidak terlihat). |
| [StrokeText](#StrokeText) | Gores teks. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Gores teks dan tambahkan ke jalur untuk pemotongan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Tambahkan teks ke jalur untuk pemotongan.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Isi teks.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Isi teks dan tambahkan ke jalur untuk pemotongan (lihat 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Isi, lalu beri gores pada teks.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Isi, lalu beri gores pada teks dan tambahkan ke jalur untuk pemotongan.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Tidak mengisi maupun memberi gores pada teks (tidak terlihat).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Gores teks.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Gores teks dan tambahkan ke jalur untuk pemotongan.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
