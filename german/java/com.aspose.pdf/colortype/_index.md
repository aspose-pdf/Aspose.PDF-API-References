---
title: "ColorType"
linktitle: "ColorType"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt den Farbtyp von Elementen auf der Seite an."
type: docs
weight: 710
url: /de/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Gibt den Farbtyp von Elementen auf der Seite an.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Schwarz‑weiß-Farbtyp. |
| [Grayscale](#Grayscale) | Graustufen‑Farbtyp. |
| [Rgb](#Rgb) | RGB‑Farbtyp. |
| [Undefined](#Undefined) | Undefinierter Farbtypwert. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Gibt den String‑Namen für den Enum‑Wert zurück. </p> <hr> Beispiel: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Schwarz‑weiß-Farbtyp.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Graustufen‑Farbtyp.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGB‑Farbtyp.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Undefinierter Farbtypwert.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Gibt den String‑Namen für den Enum‑Wert zurück. </p> <hr> Beispiel: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Enum‑Wert |

**Returns:**
Name des Wertes

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static ColorType [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
