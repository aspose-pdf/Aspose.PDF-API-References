---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase de resultado de comparar dos páginas PDF."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Representa la clase de resultado de comparar dos páginas PDF.

## Métodos

| Método | Descripción |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Convierte la matriz de diferencias a una imagen bitmap utilizando los colores especificados. |
| [dispose](#dispose--) | Ejecuta cualquier operación de limpieza necesaria antes de que el objeto sea destruido. |
| [getDestinationImage](#getDestinationImage--) | Devuelve un nuevo bitmap que representa la imagen de destino aplicando la matriz de diferencias a la imagen fuente. |
| [getDifference](#getDifference--) | Obtiene la matriz de diferencias. Esta matriz es similar a la matriz de datos de la imagen original obtenida como resultado del método LockBits. |
| [getHeight](#getHeight--) | La altura de la diferencia. |
| [getSourceImage](#getSourceImage--) | Obtiene la imagen de la primera página comparada. La imagen tiene un formato de píxel de 24 bpp. |
| [getStride](#getStride--) | El stride de los datos de la imagen de diferencia. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Convierte la matriz de diferencias a una imagen bitmap utilizando los colores especificados.

### dispose {#dispose--}
```
public final void dispose()
```

Ejecuta cualquier operación de limpieza necesaria antes de que el objeto sea destruido.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Devuelve un nuevo bitmap que representa la imagen de destino aplicando la matriz de diferencias a la imagen fuente.

**Returns:**
Una imagen de destino.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Obtiene la matriz de diferencias. Esta matriz es similar a la matriz de datos de la imagen original obtenida como resultado del método LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

La altura de la diferencia.

**Returns:**
valor int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Obtiene la imagen de la primera página comparada. La imagen tiene un formato de píxel de 24 bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

El stride de los datos de la imagen de diferencia.

**Returns:**
valor int
