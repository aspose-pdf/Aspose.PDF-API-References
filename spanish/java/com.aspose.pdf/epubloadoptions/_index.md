---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Contiene opciones para cargar/importar un archivo EPUB en un documento pdf."
type: docs
weight: 1220
url: /es/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Contiene opciones para cargar/importar un archivo EPUB en un documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Crea opciones de carga predeterminadas para convertir un archivo EPUB en documento PDF. Tamaño de página PDF predeterminado: A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Crea opciones de carga predeterminadas para convertir un archivo EPUB en documento PDF. Tamaño de página PDF predeterminado: A4 300 dpi 2480 × 3508. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Obtiene o establece el Css personalizado que se aplicará al abrir el documento Epub. |
| [getEngineType](#getEngineType--) | Seleccione el tipo de motor para la conversión de EPUB a PDF. El valor predeterminado es EngineType.NEW |
| [getMargin](#getMargin--) | Obtiene una referencia al objeto que representa la información de margen. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Representa el modo de uso del área de márgenes - define el tratamiento de las instrucciones (si las hay) del CSS del documento importado relacionadas con el uso de los márgenes. |
| [getPageSize](#getPageSize--) | Obtiene el tamaño de página de salida para la importación. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.) suelen tener un diseño flotante, por lo que permite ajustar al tamaño de página requerido. Pero a veces el contenido tiene posiciones horizontales o tamaños especificados que no permiten colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (por ejemplo, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Obtiene o establece el Css personalizado que se aplicará al abrir el documento Epub. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Seleccione el tipo de motor para la conversión de EPUB a PDF. El valor predeterminado es EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtiene una referencia al objeto que representa la información de margen. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Representa el modo de uso del área de márgenes - define el tratamiento de las instrucciones (si las hay) del CSS del documento importado relacionadas con el uso de los márgenes. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.) suelen tener un diseño flotante, por lo que permite ajustar al tamaño de página requerido. Pero a veces el contenido tiene posiciones horizontales o tamaños especificados que no permiten colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (por ejemplo, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Crea opciones de carga predeterminadas para convertir un archivo EPUB en documento PDF. Tamaño de página PDF predeterminado: A4 300 dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Crea opciones de carga predeterminadas para convertir un archivo EPUB en documento PDF. Tamaño de página PDF predeterminado: A4 300 dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Obtiene o establece el Css personalizado que se aplicará al abrir el documento Epub.

**Returns:**
valor String

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Seleccione el tipo de motor para la conversión de EPUB a PDF. El valor predeterminado es EngineType.NEW

**Returns:**
Elemento EngineType

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtiene una referencia al objeto que representa la información de margen.

**Returns:**
Objeto MarginInfo

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Representa el modo de uso del área de márgenes - define el tratamiento de las instrucciones (si las hay) del CSS del documento importado relacionadas con el uso de los márgenes.

**Returns:**
Valor MarginsAreaUsageModes @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtiene el tamaño de página de salida para la importación.

**Returns:**
Objeto Dimension2D

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.) suelen tener un diseño flotante, por lo que permite ajustar al tamaño de página requerido. Pero a veces el contenido tiene posiciones horizontales o tamaños especificados que no permiten colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (por ejemplo, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante).

**Returns:**
Valor PageSizeAdjustmentModes @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Obtiene o establece el Css personalizado que se aplicará al abrir el documento Epub.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Seleccione el tipo de motor para la conversión de EPUB a PDF. El valor predeterminado es EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtiene una referencia al objeto que representa la información de margen.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Representa el modo de uso del área de márgenes - define el tratamiento de las instrucciones (si las hay) del CSS del documento importado relacionadas con el uso de los márgenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| marginsAreaUsageMode |  | Valor MarginsAreaUsageModes @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en la capa OSHARED detectado en el documento de ejemplo. Representa el modo de uso del tamaño de página durante la conversión. Los formatos (como HTML, EPUB, etc.) suelen tener un diseño flotante, por lo que permite ajustar al tamaño de página requerido. Pero a veces el contenido tiene posiciones horizontales o tamaños especificados que no permiten colocar el contenido en el tamaño de página requerido. En tal caso podemos definir qué debe hacerse (por ejemplo, cuando el tamaño del contenido no se ajusta al tamaño de página inicial requerido del documento PDF resultante).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | Valor PageSizeAdjustmentModes @see PageSizeAdjustmentModes |
