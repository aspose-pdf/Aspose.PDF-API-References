---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin işleme modu, Tmode, metnin gösterilmesinin glif konturlarının çizilmesi, doldurulması, kırpma sınırı olarak kullanılması ya da üçünün bir kombinasyonu olup olmayacağını belirler."
type: docs
weight: 5240
url: /tr/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

Metin işleme modu, Tmode, metnin gösterilmesinin glif konturlarının çizilmesi, doldurulması, kırpma sınırı olarak kullanılması ya da üçünün bir kombinasyonu olup olmayacağını belirler.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Kırpma için yola metin ekle. |
| [FillText](#FillText) | Metni doldur. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Metni doldur ve kırpma için yola ekle (bkz. 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Metni doldur, ardından kenarını çiz. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Metni doldur, ardından kenarını çiz ve kırpma için yola ekle. |
| [Invisible](#Invisible) | Ne doldur ne de kenarını çiz (görünmez). |
| [StrokeText](#StrokeText) | Metnin kenarını çiz. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Metnin kenarını çiz ve kırpma için yola ekle. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Kırpma için yola metin ekle.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Metni doldur.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Metni doldur ve kırpma için yola ekle (bkz. 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Metni doldur, ardından kenarını çiz.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Metni doldur, ardından kenarını çiz ve kırpma için yola ekle.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Ne doldur ne de kenarını çiz (görünmez).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Metnin kenarını çiz.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Metnin kenarını çiz ve kırpma için yola ekle.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
