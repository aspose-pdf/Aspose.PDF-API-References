---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar (importar) un archivo PCL en un documento PDF."
type: docs
weight: 3530
url: /es/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Representa opciones para cargar (importar) un archivo PCL en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Crea el objeto {@code PclLoadOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [getConversionEngine](#getConversionEngine--) | Define el motor de conversión que se utilizará para la conversión |
| [getExceptions](#getExceptions--) | Lista de errores de conversión. |
| [isSupressErrors](#isSupressErrors--) | Obtiene o establece el valor booleano que indica si los errores de conversión PCL deben suprimirse. |
| [setBatchSize](#setBatchSize-int-) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [setConversionEngine](#setConversionEngine-int-) | Define el motor de conversión que se utilizará para la conversión |
| [setSupressErrors](#setSupressErrors-boolean-) | Obtiene o establece el valor booleano que indica si los errores de conversión PCL deben suprimirse. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Crea el objeto {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Returns:**
valor int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Define el motor de conversión que se utilizará para la conversión

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Lista de errores de conversión.

**Returns:**
Lista de Excepciones

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Obtiene o establece el valor booleano que indica si los errores de conversión PCL deben suprimirse.

**Returns:**
valor booleano

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Define el motor de conversión que se utilizará para la conversión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Obtiene o establece el valor booleano que indica si los errores de conversión PCL deben suprimirse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| supressErrors |  | valor booleano |
