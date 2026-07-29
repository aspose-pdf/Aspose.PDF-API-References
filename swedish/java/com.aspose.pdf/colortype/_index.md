---
title: "ColorType"
linktitle: "ColorType"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger färgtyp för element på sidan."
type: docs
weight: 710
url: /sv/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Anger färgtyp för element på sidan.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Svartvitt färgtyp. |
| [Grayscale](#Grayscale) | Gråskala färgtyp. |
| [Rgb](#Rgb) | RGB-färgtyp. |
| [Undefined](#Undefined) | Odefinierat färgtypvärde. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Returnerar strängnamn för enum‑värdet. </p> <hr> Exempel: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Svartvitt färgtyp.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Gråskala färgtyp.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGB-färgtyp.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Odefinierat färgtypvärde.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Returnerar strängnamn för enum‑värdet. </p> <hr> Exempel: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Enum‑värde |

**Returns:**
Värdets namn

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static ColorType [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
