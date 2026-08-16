---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para generar la representación HTML de las diferencias de textos. Los saltos de línea eliminados se indican con el signo - de marca de párrafo."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Representa una clase para generar la representación HTML de las diferencias de textos. Los saltos de línea eliminados se indican con el signo - de marca de párrafo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Crea una instancia de la clase {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Crea una instancia de la clase {@link HtmlDiffOutputGenerator}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Genera la salida basada en las diferencias entre los textos y la guarda en un archivo. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Genera la salida basada en las diferencias entre los textos y la guarda en un archivo. |
| [generateOutput1](#generateOutput1-java.util.List-) | Genera la salida basada en las diferencias entre los textos y la guarda en un archivo. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Genera la salida basada en las diferencias entre los textos y la guarda en un archivo. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Método interno |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Crea una instancia de la clase {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Crea una instancia de la clase {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
Genera la salida basada en las diferencias entre los textos y la guarda en un archivo.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Genera la salida basada en las diferencias entre los textos y la guarda en un archivo.

### generateOutput1 {#generateOutput1-java.util.List-}
Genera la salida basada en las diferencias entre los textos y la guarda en un archivo.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Genera la salida basada en las diferencias entre los textos y la guarda en un archivo.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Método interno

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es {@code False}.

**Returns:**
valor booleano

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Obtiene y establece la cadena de estilo CSS para la operación Delete. Ejemplo: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Obtiene y establece la cadena de estilo CSS para la operación Equal. Ejemplo: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Obtiene y establece la cadena de estilo CSS para la operación Insert. Ejemplo: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Obtenga o establezca el estilo text-decoration: line-through para la operación delete. El valor predeterminado es {@code False}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
