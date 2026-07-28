---
title: "TextReplaceOptions.Scope"
linktitle: "TextReplaceOptions.Scope"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Ámbito donde se aplica la operación de reemplazo de texto REPLACE_FIRST por defecto. Esta opción obsoleta se mantuvo por compatibilidad. Afecta a PdfContentEditor y no tiene efecto en."
type: docs
weight: 5280
url: /es/java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.Scope > com.aspose.pdf.TextReplaceOptions.Scope, java.lang.Enum < TextReplaceOptions.Scope >, com.aspose.pdf.TextReplaceOptions.Scope

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.Scope >

```
public static enum TextReplaceOptions.Scope extends Enum < TextReplaceOptions.Scope >
```

Ámbito donde se aplica la operación de reemplazo de texto REPLACE_FIRST por defecto. Esta opción obsoleta se mantuvo por compatibilidad. Afecta a PdfContentEditor y no tiene efecto en TextFragmentAbsorber.

## Campos

| Campo | Descripción |
| --- | --- |
| [REPLACE_ALL](#REPLACE_ALL) | Reemplazar todas las ocurrencias de texto en todas las páginas afectadas |
| [REPLACE_FIRST](#REPLACE_FIRST) | Reemplazar solo la primera aparición del texto en cada una de las páginas afectadas |

## Métodos

| Método | Descripción |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### REPLACE_ALL {#REPLACE_ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```

Reemplazar todas las ocurrencias de texto en todas las páginas afectadas

### REPLACE_FIRST {#REPLACE_FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```

Reemplazar solo la primera aparición del texto en cada una de las páginas afectadas

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static TextReplaceOptions.Scope [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
