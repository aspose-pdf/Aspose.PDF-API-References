---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato XPS"
type: docs
weight: 5770
url: /es/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opciones de guardado para exportar al formato XPS

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [getDefaultFont](#getDefaultFont--) | Obtiene/establece el nombre de fuente predeterminado. Se usa si el nombre de fuente incrustada no se encuentra en el sistema. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indica si se debe conservar el texto transparente (con OCR). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Obtiene o establece la opción UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Obtiene/establece el nombre de fuente predeterminado. Se usa si el nombre de fuente incrustada no se encuentra en el sistema. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indica si se debe conservar el texto transparente (con OCR). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Obtiene o establece la opción UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Constructor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Returns:**
valor int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Obtiene/establece el nombre de fuente predeterminado. Se usa si el nombre de fuente incrustada no se encuentra en el sistema.

**Returns:**
valor String

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indica si se debe conservar el texto transparente (con OCR).

**Returns:**
valor booleano

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión.

**Returns:**
valor booleano

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Obtiene o establece la opción UseNewImagingEngine.

**Returns:**
valor booleano @deprecated UseNewImagingEngine está obsoleto

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Obtiene/establece el nombre de fuente predeterminado. Se usa si el nombre de fuente incrustada no se encuentra en el sistema.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indica si se debe conservar el texto transparente (con OCR).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Obtiene/establece la bandera para usar fuentes TrueType incrustadas. Evitar el uso de fuentes TrueType incrustadas puede reducir el tiempo de conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Obtiene o establece la opción UseNewImagingEngine.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano @deprecated UseNewImagingEngine está obsoleto |
