---
title: "ColorType"
linktitle: "ColorType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica il tipo di colore degli elementi nella pagina."
type: docs
weight: 710
url: /it/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Specifica il tipo di colore degli elementi nella pagina.

## Campi

| Campo | Descrizione |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Tipo di colore in bianco e nero. |
| [Grayscale](#Grayscale) | Tipo di colore in scala di grigi. |
| [Rgb](#Rgb) | Tipo di colore RGB. |
| [Undefined](#Undefined) | Valore del tipo di colore non definito. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Restituisce il nome String per il valore enum. </p> <hr> Esempio: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Tipo di colore in bianco e nero.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Tipo di colore in scala di grigi.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

Tipo di colore RGB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Valore del tipo di colore non definito.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Restituisce il nome String per il valore enum. </p> <hr> Esempio: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore enum |

**Returns:**
Nome del valore

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static ColorType [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
