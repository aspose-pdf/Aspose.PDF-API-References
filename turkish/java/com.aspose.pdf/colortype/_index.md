---
title: "ColorType"
linktitle: "ColorType"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfadaki öğelerin renk tipini belirtir."
type: docs
weight: 710
url: /tr/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Sayfadaki öğelerin renk tipini belirtir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Siyah beyaz renk türü. |
| [Grayscale](#Grayscale) | Gri tonlamalı renk türü. |
| [Rgb](#Rgb) | RGB renk türü. |
| [Undefined](#Undefined) | Tanımsız renk türü değeri. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Enum değerinin String adını döndürür. </p> <hr> Örnek: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Siyah beyaz renk türü.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Gri tonlamalı renk türü.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGB renk türü.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Tanımsız renk türü değeri.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Enum değerinin String adını döndürür. </p> <hr> Örnek: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Enum değeri |

**Returns:**
Değerin adı

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static ColorType [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
