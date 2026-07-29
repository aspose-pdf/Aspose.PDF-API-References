---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "La clase contiene un conjunto de opciones para la compresión de imágenes."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

La clase contiene un conjunto de opciones para la compresión de imágenes.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getEncoding](#getEncoding--) | Obtiene o establece la codificación utilizada para almacenar imágenes. |
| [getImageQuality](#getImageQuality--) | Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressImages. |
| [getMaxResolution](#getMaxResolution--) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [getResizeImages](#getResizeImages--) | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [getVersion](#getVersion--) | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\"). |
| [isCompressImages](#isCompressImages--) | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [setEncoding](#setEncoding-int-) | Obtiene o establece la codificación utilizada para almacenar imágenes. |
| [setImageQuality](#setImageQuality-int-) | Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressImages. |
| [setMaxResolution](#setMaxResolution-int-) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [setResizeImages](#setResizeImages-boolean-) | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [setVersion](#setVersion-int-) | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\"). |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Obtiene o establece la codificación utilizada para almacenar imágenes.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressImages.

**Returns:**
valor int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada.

**Returns:**
valor int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado.

**Returns:**
valor booleano

### getVersion {#getVersion--}
```
public final int getVersion()
```

Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\").

**Returns:**
valor int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality.

**Returns:**
valor booleano

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Obtiene o establece la codificación utilizada para almacenar imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressImages.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\").

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
