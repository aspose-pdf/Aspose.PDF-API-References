---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El modo de renderizado de texto, Tmode, determina si la visualización del texto debe provocar que los contornos de los glifos se tracen, rellenen, se usen como límite de recorte, o alguna combinación de los tres."
type: docs
weight: 5240
url: /es/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

El modo de renderizado de texto, Tmode, determina si la visualización del texto debe provocar que los contornos de los glifos se tracen, rellenen, se usen como límite de recorte, o alguna combinación de los tres.

## Campos

| Campo | Descripción |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Agregar texto a la ruta para recorte. |
| [FillText](#FillText) | Rellenar texto. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Rellenar texto y agregar a la ruta para recorte (ver 9.3.6, "Modo de renderizado de texto,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Rellenar, luego trazar texto. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Rellenar, luego trazar texto y agregar a la ruta para recorte. |
| [Invisible](#Invisible) | Ni rellenar ni trazar texto (invisible). |
| [StrokeText](#StrokeText) | Trazar texto. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Trazar texto y agregar a la ruta para recorte. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Agregar texto a la ruta para recorte.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Rellenar texto.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Rellenar texto y agregar a la ruta para recorte (ver 9.3.6, "Modo de renderizado de texto,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Rellenar, luego trazar texto.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Rellenar, luego trazar texto y agregar a la ruta para recorte.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Ni rellenar ni trazar texto (invisible).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Trazar texto.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Trazar texto y agregar a la ruta para recorte.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
