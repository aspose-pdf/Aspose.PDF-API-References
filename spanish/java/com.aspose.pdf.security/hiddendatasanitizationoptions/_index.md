---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa las opciones de configuración para sanitizar datos ocultos dentro de un documento."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Representa las opciones de configuración para sanitizar datos ocultos dentro de un documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [all](#all--) | Crea una nueva instancia de la clase {@link HiddenDataSanitizationOptions} con todas las opciones configuradas para la sanitización. Esto incluye habilitar la eliminación de anotaciones, JavaScript, metadatos, archivos adjuntos, índice de búsqueda, información privada, aplanado de formularios y capas, mientras se deshabilita la opción de convertir páginas a imágenes. Configuraciones opcionales como {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) o {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) pueden modificarse manualmente después de obtener la instancia, ya que no están activas por defecto. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Obtiene la opción de convertir páginas a imágenes. Si esta opción está habilitada, se ignorará la opción ImageCompressionOptions. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, que son controlados por otras opciones. |
| [getFlattenForms](#getFlattenForms--) | Obtiene un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar los formularios convierte los campos interactivos en contenido estático, haciéndolos no editables ni rellenables. |
| [getFlattenLayers](#getFlattenLayers--) | Obtiene la opción de aplanar las capas en el documento PDF. Cuando está habilitada, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos al simplificar su contenido y garantizar que no haya datos ocultos dentro de las capas. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Obtiene la opción de conversión de imágenes del documento. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. |
| [getImageDpi](#getImageDpi--) | Obtiene la opción de resolver imágenes de página durante la conversión. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Obtiene un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitada, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción. |
| [getRemoveAttachments](#getRemoveAttachments--) | Obtiene la opción de eliminar todos los archivos adjuntos del documento. Cuando está habilitada, garantiza que cualquier adjunto dentro del PDF sea eliminado durante el proceso de sanitización. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Obtiene un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados. |
| [getRemoveMetadata](#getRemoveMetadata--) | Obtiene una opción para eliminar metadatos del documento. Si se establece en true, los metadatos como las propiedades del documento y la información adicional de metadatos incrustados se eliminarán durante la sanitización. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Obtiene un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Habilita la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y privacidad del documento. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Establece la opción de convertir páginas a imágenes. Si esta opción está habilitada, se ignorará la opción ImageCompressionOptions. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, que son controlados por otras opciones. |
| [setFlattenForms](#setFlattenForms-boolean-) | Establece un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar los formularios convierte los campos interactivos en contenido estático, haciéndolos no editables ni rellenables. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Establece la opción de aplanar las capas en el documento PDF. Cuando está habilitada, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos al simplificar su contenido y garantizar que no haya datos ocultos dentro de las capas. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Establece la opción de conversión de imágenes del documento. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. |
| [setImageDpi](#setImageDpi-int-) | Establece la opción de resolver imágenes de página durante la conversión. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Establece un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitada, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Establece la opción de eliminar todos los archivos adjuntos del documento. Cuando está habilitada, garantiza que cualquier adjunto dentro del PDF se elimine durante el proceso de saneamiento. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Establece un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Establece una opción para eliminar los metadatos del documento. Si se establece en verdadero, los metadatos como las propiedades del documento y la información adicional de metadatos incrustados se eliminarán durante el saneamiento. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Establece un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Permite la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y la privacidad del documento. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Crea una nueva instancia de la clase {@link HiddenDataSanitizationOptions} con todas las opciones configuradas para la sanitización. Esto incluye habilitar la eliminación de anotaciones, JavaScript, metadatos, archivos adjuntos, índice de búsqueda, información privada, aplanado de formularios y capas, mientras se deshabilita la opción de convertir páginas a imágenes. Configuraciones opcionales como {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) o {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) pueden modificarse manualmente después de obtener la instancia, ya que no están activas por defecto.

**Returns:**
Una instancia de {@link HiddenDataSanitizationOptions} con todas las opciones de saneamiento preconfiguradas.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Obtiene la opción de convertir páginas a imágenes. Si esta opción está habilitada, se ignorará la opción ImageCompressionOptions. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, que son controlados por otras opciones.

**Returns:**
la opción de convertir páginas a imágenes.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Obtiene un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar los formularios convierte los campos interactivos en contenido estático, haciéndolos no editables ni rellenables.

**Returns:**
un valor que indica si los formularios en el documento deben aplanarse durante el proceso de saneamiento.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Obtiene la opción de aplanar las capas en el documento PDF. Cuando está habilitada, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos al simplificar su contenido y garantizar que no haya datos ocultos dentro de las capas.

**Returns:**
la opción de aplanar las capas en el documento PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Obtiene la opción de conversión de imágenes del documento. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida.

**Returns:**
la opción de conversión de imágenes del documento.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Obtiene la opción de resolver imágenes de página durante la conversión.

**Returns:**
la opción de resolver imágenes de página durante la conversión.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Obtiene un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitada, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción.

**Returns:**
un valor que indica si se deben eliminar las anotaciones del documento.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Obtiene la opción de eliminar todos los archivos adjuntos del documento. Cuando está habilitada, garantiza que cualquier adjunto dentro del PDF sea eliminado durante el proceso de sanitización.

**Returns:**
la opción de eliminar todos los archivos adjuntos del documento.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Obtiene un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados.

**Returns:**
un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Obtiene una opción para eliminar metadatos del documento. Si se establece en true, los metadatos como las propiedades del documento y la información adicional de metadatos incrustados se eliminarán durante la sanitización.

**Returns:**
una opción para eliminar los metadatos del documento.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Obtiene un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Habilita la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y privacidad del documento.

**Returns:**
un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Establece la opción de convertir páginas a imágenes. Si esta opción está habilitada, se ignorará la opción ImageCompressionOptions. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, que son controlados por otras opciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | la opción de convertir páginas a imágenes. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Establece un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar los formularios convierte los campos interactivos en contenido estático, haciéndolos no editables ni rellenables.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | un valor que indica si los formularios en el documento deben aplanarse durante el proceso de saneamiento. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Establece la opción de aplanar las capas en el documento PDF. Cuando está habilitada, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos al simplificar su contenido y garantizar que no haya datos ocultos dentro de las capas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | la opción de aplanar las capas en el documento PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Establece la opción de conversión de imágenes del documento. La opción debe habilitarse manualmente al usar el método {@code #All()} si es requerida.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Establece la opción de resolver imágenes de página durante la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | la opción de resolver imágenes de página durante la conversión. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Establece un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitada, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | un valor que indica si se deben eliminar las anotaciones del documento. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Establece la opción de eliminar todos los archivos adjuntos del documento. Cuando está habilitada, garantiza que cualquier adjunto dentro del PDF se elimine durante el proceso de saneamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | la opción de eliminar todos los archivos adjuntos del documento. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Establece un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Establece una opción para eliminar los metadatos del documento. Si se establece en verdadero, los metadatos como las propiedades del documento y la información adicional de metadatos incrustados se eliminarán durante el saneamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | una opción para eliminar los metadatos del documento. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Establece un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Permite la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y la privacidad del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. |
