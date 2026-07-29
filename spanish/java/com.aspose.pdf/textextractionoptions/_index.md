---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones de extracción de texto"
type: docs
weight: 5060
url: /es/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Representa opciones de extracción de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Inicializa una nueva instancia del objeto {@code TextExtractionOptions} para el modo de formato de texto especificado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Obtiene el modo de formato. |
| [getScaleFactor](#getScaleFactor--) | Obtiene el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor produce más espacios en el texto extraído. El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente. |
| [setFormattingMode](#setFormattingMode-int-) | Establece el modo de formato. |
| [setScaleFactor](#setScaleFactor-double-) | Establece el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor produce más espacios en el texto extraído (de 1 a 10). El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Inicializa una nueva instancia del objeto {@code TextExtractionOptions} para el modo de formato de texto especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattingMode |  | Valor del modo de formato de texto. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Obtiene el modo de formato.

**Returns:**
Valor de TextFormattingMode @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Obtiene el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor produce más espacios en el texto extraído. El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente.

**Returns:**
valor double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Establece el modo de formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor de TextFormattingMode @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Establece el factor que se aplicará para escalar el tamaño de la fuente durante la extracción en modo puro. Un valor menor produce más espacios en el texto extraído (de 1 a 10). El valor predeterminado es 1 - sin escalado; establecer el valor a cero permite que el algoritmo elija el escalado automáticamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
