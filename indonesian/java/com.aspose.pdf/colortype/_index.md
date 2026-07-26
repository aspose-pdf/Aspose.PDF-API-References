---
title: "ColorType"
linktitle: "ColorType"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan tipe warna elemen pada halaman."
type: docs
weight: 710
url: /id/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Menentukan tipe warna elemen pada halaman.

## Fields

| Field | Deskripsi |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Tipe warna hitam putih. |
| [Grayscale](#Grayscale) | Tipe warna skala abu-abu. |
| [Rgb](#Rgb) | Tipe warna RGB. |
| [Undefined](#Undefined) | Nilai tipe warna tidak terdefinisi. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Mengembalikan nama String untuk nilai enum. </p> <hr> Contoh: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Tipe warna hitam putih.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Tipe warna skala abu-abu.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

Tipe warna RGB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Nilai tipe warna tidak terdefinisi.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Mengembalikan nama String untuk nilai enum. </p> <hr> Contoh: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai enum |

**Returns:**
Nama nilai

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static ColorType [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
