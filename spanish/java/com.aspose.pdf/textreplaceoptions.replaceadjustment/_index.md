---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Determina la acción que se realizará después de reemplazar un fragmento de texto a más corto. None - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta hacerlo."
type: docs
weight: 5270
url: /es/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Determina la acción que se realizará después de reemplazar un fragmento de texto por uno más corto. None - sin acción, el texto reemplazado puede superponerse al resto de la línea; AdjustSpaceWidth - intenta ajustar los espacios entre palabras para mantener la longitud de la línea; WholeWordsHyphenation - intenta distribuir las palabras entre las líneas del párrafo para mantener el margen derecho del párrafo; ShiftRestOfLine - desplaza el resto de la línea según la longitud cambiada del texto, la longitud de la línea puede modificarse; El valor predeterminado es ShiftRestOfLine.

## Campos

| Campo | Descripción |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Intenta ajustar los espacios entre palabras para mantener la longitud de la línea. |
| [IsFormFillingMode](#IsFormFillingMode) | Intenta distribuir las palabras en el espacio blanco disponible usando el ancho del párrafo. Si el texto se desborda, se ocultará. |
| [None](#None) | Sin acción, el texto reemplazado puede superponerse al resto de la línea. |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Predeterminado) Desplaza el resto de la línea según la longitud cambiante del texto, la longitud de la línea puede cambiar. |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Intenta distribuir palabras entre las líneas del párrafo para mantener el margen derecho del párrafo. |

## Métodos

| Método | Descripción |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Intenta ajustar los espacios entre palabras para mantener la longitud de la línea.

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Intenta distribuir las palabras en el espacio blanco disponible usando el ancho del párrafo. Si el texto se desborda, se ocultará.

### None {#None}
```
public static final int None
```

Sin acción, el texto reemplazado puede superponerse al resto de la línea.

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Predeterminado) Desplaza el resto de la línea según la longitud cambiante del texto, la longitud de la línea puede cambiar.

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Intenta distribuir palabras entre las líneas del párrafo para mantener el margen derecho del párrafo.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bandera |  |  |
| flagToCheck |  |  |
