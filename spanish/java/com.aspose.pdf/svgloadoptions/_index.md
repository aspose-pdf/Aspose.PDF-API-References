---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar/importar un archivo SVG en un documento PDF."
type: docs
weight: 4700
url: /es/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Representa opciones para cargar/importar un archivo SVG en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Crea el objeto {@code SvgLoadOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Permite seleccionar el motor de conversión que se utilizará durante la conversión. Actualmente el nuevo motor está en fase de pruebas B, por lo que este valor se establece por defecto en ConversionEngines.LegacyEngine. |
| [getPageInfo](#getPageInfo--) | Obtiene la información de página que debe aplicarse al cargar el documento. |
| [isAdjustPageSize](#isAdjustPageSize--) | Ajusta el tamaño de la página PDF al tamaño SVG. |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Ajusta el tamaño de la página PDF al tamaño SVG. |
| [setConversionEngine](#setConversionEngine-int-) | Permite seleccionar el motor de conversión que se utilizará durante la conversión. Actualmente el nuevo motor está en fase de pruebas B, por lo que este valor se establece por defecto en ConversionEngines.LegacyEngine. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Establece la información de página que debe aplicarse al cargar el documento. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Crea el objeto {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Permite seleccionar el motor de conversión que se utilizará durante la conversión. Actualmente el nuevo motor está en fase de pruebas B, por lo que este valor se establece por defecto en ConversionEngines.LegacyEngine.

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtiene la información de página que debe aplicarse al cargar el documento.

**Returns:**
Objeto PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Ajusta el tamaño de la página PDF al tamaño SVG.

**Returns:**
valor booleano

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Ajusta el tamaño de la página PDF al tamaño SVG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Permite seleccionar el motor de conversión que se utilizará durante la conversión. Actualmente el nuevo motor está en fase de pruebas B, por lo que este valor se establece por defecto en ConversionEngines.LegacyEngine.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Establece la información de página que debe aplicarse al cargar el documento.
