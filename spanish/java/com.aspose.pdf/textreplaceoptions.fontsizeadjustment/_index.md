---
title: "TextReplaceOptions.FontSizeAdjustment"
linktitle: "TextReplaceOptions.FontSizeAdjustment"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica una política sobre cómo debe ajustarse el tamaño de fuente del texto para encajar dentro de un área contenedora."
type: docs
weight: 5260
url: /es/java/com.aspose.pdf/textreplaceoptions.fontsizeadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment > com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment >, com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.FontSizeAdjustment >

```
public static enum TextReplaceOptions.FontSizeAdjustment extends Enum < TextReplaceOptions.FontSizeAdjustment >
```

Especifica una política sobre cómo debe ajustarse el tamaño de fuente del texto para encajar dentro de un área contenedora.

## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | El tamaño de fuente no se cambia. |
| [ScaleToFill](#ScaleToFill) | El tamaño de fuente se ajusta (tanto reduciéndolo como aumentándolo) para que el texto llene los límites del rectángulo tanto como sea posible. |
| [ShrinkToFit](#ShrinkToFit) | El tamaño de fuente se reduce si el texto es demasiado grande para caber en los límites. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### None {#None}
```
public static final TextReplaceOptions.FontSizeAdjustment None
```

El tamaño de fuente no se cambia.

### ScaleToFill {#ScaleToFill}
```
public static final TextReplaceOptions.FontSizeAdjustment ScaleToFill
```

El tamaño de fuente se ajusta (tanto reduciéndolo como aumentándolo) para que el texto llene los límites del rectángulo tanto como sea posible.

### ShrinkToFit {#ShrinkToFit}
```
public static final TextReplaceOptions.FontSizeAdjustment ShrinkToFit
```

El tamaño de fuente se reduce si el texto es demasiado grande para caber en los límites.

### getByValue {#getByValue-int-}
```
public static TextReplaceOptions.FontSizeAdjustment getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static TextReplaceOptions.FontSizeAdjustment [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
