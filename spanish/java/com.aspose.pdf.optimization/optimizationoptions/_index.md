---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources()."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources().

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [all](#all--) | Crea una estrategia de optimización con todas las opciones activadas. Tenga en cuenta que solo se activan las opciones que no cambian ninguna funcionalidad del documento. Por ejemplo, la compresión de imágenes y la desincorporación de fuentes no se habilitarán (y pueden incorporarse manualmente). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Si se establece en {@link}, todas las secuencias de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante {@code Document#OptimizeResources()}. El valor predeterminado es {@link} para preservar la compatibilidad hacia atrás. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión. |
| [getImageEncoding](#getImageEncoding--) | Codificación de imagen que se utilizará. |
| [getImageQuality](#getImageQuality--) | Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges. |
| [getMaxResoultion](#getMaxResoultion--) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales. |
| [isCompressImages](#isCompressImages--) | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Si esta bandera se establece en {@code }, los objetos Pdf se empaquetarán en Objest Streams y se comprimirán para reducir el tamaño del archivo pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Si esta bandera se establece en true, los flujos de recursos serán analizados. Si se encuentran flujos duplicados (p.ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Eliminar información privada (información de pieza de página). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Si esta bandera se establece en true, todos los objetos del documento serán verificados y los objetos no utilizados (p.ej., objetos que no tienen ninguna referencia) se eliminan del documento. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Si esta bandera se establece en true, cada recurso se verifica en su uso. Si el recurso nunca se usa, entonces el recurso se elimina. Esto puede reducir el tamaño del documento, por ejemplo cuando se extrajeron páginas del documento. |
| [isResizeImages](#isResizeImages--) | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [isSubsetFonts](#isSubsetFonts--) | Las fuentes se convertirán en subconjuntos si se establece en true. |
| [isUnembedFonts](#isUnembedFonts--) | No incruste fuentes si se establece en true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Si se establece en {@link}, todas las secuencias de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante {@code Document#OptimizeResources()}. El valor predeterminado es {@link} para preservar la compatibilidad hacia atrás. |
| [setCompressImages](#setCompressImages-boolean-) | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Si esta bandera se establece en {@code }, los objetos Pdf se empaquetarán en Objest Streams y se comprimirán para reducir el tamaño del archivo pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión. |
| [setImageEncoding](#setImageEncoding-int-) | Codificación de imagen que se utilizará. |
| [setImageQuality](#setImageQuality-int-) | Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Si esta bandera se establece en true, los flujos de recursos serán analizados. Si se encuentran flujos duplicados (p.ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces). |
| [setMaxResoultion](#setMaxResoultion-int-) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Eliminar información privada (información de pieza de página). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Si esta bandera se establece en true, todos los objetos del documento serán verificados y los objetos no utilizados (p.ej., objetos que no tienen ninguna referencia) se eliminan del documento. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Si esta bandera se establece en true, cada recurso se verifica en su uso. Si el recurso nunca se usa, entonces el recurso se elimina. Esto puede reducir el tamaño del documento, por ejemplo cuando se extrajeron páginas del documento. |
| [setResizeImages](#setResizeImages-boolean-) | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Las fuentes se convertirán en subconjuntos si se establece en true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | No incruste fuentes si se establece en true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Crea una estrategia de optimización con todas las opciones activadas. Tenga en cuenta que solo se activan las opciones que no cambian ninguna funcionalidad del documento. Por ejemplo, la compresión de imágenes y la desincorporación de fuentes no se habilitarán (y pueden incorporarse manualmente).

**Returns:**
Objeto OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Si se establece en {@link}, todas las secuencias de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante {@code Document#OptimizeResources()}. El valor predeterminado es {@link} para preservar la compatibilidad hacia atrás.

**Returns:**
valor booleano

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión.

**Returns:**
Instancia ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Codificación de imagen que se utilizará.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges.

**Returns:**
valor int @deprecated Por favor use ImageCompressionOptions.ImageQuality en su lugar.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada.

**Returns:**
valor int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales.

**Returns:**
valor booleano

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality.

**Returns:**
valor boolean @deprecated Por favor use ImageCompressionOptions.CompressImages en su lugar.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Si esta bandera se establece en {@code }, los objetos Pdf se empaquetarán en Objest Streams y se comprimirán para reducir el tamaño del archivo pdf.

**Returns:**
valor booleano

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Si esta bandera se establece en true, los flujos de recursos serán analizados. Si se encuentran flujos duplicados (p.ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces).

**Returns:**
valor booleano

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Eliminar información privada (información de pieza de página).

**Returns:**
valor booleano

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Si esta bandera se establece en true, todos los objetos del documento serán verificados y los objetos no utilizados (p.ej., objetos que no tienen ninguna referencia) se eliminan del documento.

**Returns:**
valor booleano

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Si esta bandera se establece en true, cada recurso se verifica en su uso. Si el recurso nunca se usa, entonces el recurso se elimina. Esto puede reducir el tamaño del documento, por ejemplo cuando se extrajeron páginas del documento.

**Returns:**
valor booleano

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado.

**Returns:**
valor boolean @deprecated Por favor use ImageCompressionOptions.ResizeImages en su lugar.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Las fuentes se convertirán en subconjuntos si se establece en true.

**Returns:**
valor booleano

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

No incruste fuentes si se establece en true.

**Returns:**
valor booleano

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Si se establece en {@link}, todas las secuencias de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante {@code Document#OptimizeResources()}. El valor predeterminado es {@link} para preservar la compatibilidad hacia atrás.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor boolean @deprecated Por favor use ImageCompressionOptions.CompressImages en su lugar. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Si esta bandera se establece en {@code }, los objetos Pdf se empaquetarán en Objest Streams y se comprimirán para reducir el tamaño del archivo pdf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Codificación de imagen que se utilizará.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @deprecated Por favor use ImageCompressionOptions.ImageQuality en su lugar. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Si esta bandera se establece en true, los flujos de recursos serán analizados. Si se encuentran flujos duplicados (p.ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Eliminar información privada (información de pieza de página).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Si esta bandera se establece en true, todos los objetos del documento serán verificados y los objetos no utilizados (p.ej., objetos que no tienen ninguna referencia) se eliminan del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Si esta bandera se establece en true, cada recurso se verifica en su uso. Si el recurso nunca se usa, entonces el recurso se elimina. Esto puede reducir el tamaño del documento, por ejemplo cuando se extrajeron páginas del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor boolean @deprecated Por favor use ImageCompressionOptions.ResizeImages en su lugar. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Las fuentes se convertirán en subconjuntos si se establece en true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

No incruste fuentes si se establece en true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
