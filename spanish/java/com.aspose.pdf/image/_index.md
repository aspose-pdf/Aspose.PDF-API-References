---
title: "Image"
linktitle: "Image"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una imagen."
type: docs
weight: 2280
url: /es/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Representa una imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Image](#Image--) | constructor predeterminado |

## Métodos

| Método | Descripción |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Intenta convertir una imagen bmp/png/gif/tiff a un flujo con formato de imagen JPG. |
| [deepClone](#deepClone--) | Clona la imagen. |
| [getBitmapInfo](#getBitmapInfo--) | Obtiene o establece los bytes de imagen sin comprimir. |
| [getBitmapSize](#getBitmapSize--) | Obtiene el tamaño del mapa de bits de la imagen. |
| [getBufferedImage](#getBufferedImage--) | Obtiene la imagen java awt. |
| [getFile](#getFile--) | Obtiene el archivo de imagen. |
| [getFileType](#getFileType--) | Obtiene el tipo de archivo de imagen. |
| [getFixHeight](#getFixHeight--) | Obtiene la altura de la imagen. |
| [getFixWidth](#getFixWidth--) | Obtiene el ancho de la imagen. |
| [getImageScale](#getImageScale--) | Obtiene la escala de la imagen. |
| [getImageStream](#getImageStream--) | Obtiene el flujo de la imagen. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Devuelve el tipo mime de la imagen. |
| [getTitle](#getTitle--) | Obtiene un valor de cadena que indica el título de la imagen. |
| [isApplyResolution](#isApplyResolution--) | Obtiene o establece un valor booleano que indica si la imagen usa resolución durante la generación. |
| [isBlackWhite](#isBlackWhite--) | Obtiene un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Intenta detectar y usar codificación 1bpp para imágenes en escala de grises. Valor predeterminado == FALSE. |
| [setApplyResolution](#setApplyResolution-boolean-) | Obtiene o establece un valor booleano que indica si la imagen usa resolución durante la generación. |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Obtiene o establece los bytes de imagen sin comprimir. |
| [setBlackWhite](#setBlackWhite-boolean-) | Establece un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Intenta detectar y usar codificación 1bpp para imágenes en escala de grises. Valor predeterminado == FALSE. |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Establece la imagen java awt. |
| [setFile](#setFile-java.lang.String-) | Establece el archivo de imagen. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Establece el tipo de archivo de imagen. |
| [setFixHeight](#setFixHeight-double-) | Establece la altura de la imagen. |
| [setFixWidth](#setFixWidth-double-) | Establece el ancho de la imagen. |
| [setImageScale](#setImageScale-double-) | Establece la escala de la imagen. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Establece el flujo de la imagen. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Establece un valor de cadena que indica el título de la imagen. |

### Image {#Image--}
```
public Image()
```

constructor predeterminado

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Intenta convertir una imagen bmp/png/gif/tiff a un flujo con formato de imagen JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la imagen.

**Returns:**
El objeto clonado

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Obtiene o establece los bytes de imagen sin comprimir.

**Returns:**
Instancia de BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Obtiene el tamaño del mapa de bits de la imagen.

**Returns:**
Instancia de Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Obtiene la imagen java awt.

**Returns:**
Objeto BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

Obtiene el archivo de imagen.

**Returns:**
valor String

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Obtiene el tipo de archivo de imagen.

**Returns:**
valor int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Obtiene la altura de la imagen.

**Returns:**
valor double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Obtiene el ancho de la imagen.

**Returns:**
valor double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Obtiene la escala de la imagen.

**Returns:**
valor double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Obtiene el flujo de la imagen.

**Returns:**
Objeto InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Devuelve el tipo mime de la imagen.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtiene un valor de cadena que indica el título de la imagen.

**Returns:**
valor TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Obtiene o establece un valor booleano que indica si la imagen usa resolución durante la generación.

**Returns:**
valor booleano

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Obtiene un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en true.

**Returns:**
valor booleano

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Intenta detectar y usar codificación 1bpp para imágenes en escala de grises. Valor predeterminado == FALSE.

**Returns:**
valor booleano

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Obtiene o establece un valor booleano que indica si la imagen usa resolución durante la generación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Obtiene o establece los bytes de imagen sin comprimir.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Establece un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Intenta detectar y usar codificación 1bpp para imágenes en escala de grises. Valor predeterminado == FALSE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| blackWhiteForGrayScale |  | valor booleano |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Establece la imagen java awt.

### setFile {#setFile-java.lang.String-}
Establece el archivo de imagen.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Establece el tipo de archivo de imagen.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Establece la altura de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Establece el ancho de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Establece la escala de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setImageStream {#setImageStream-java.io.InputStream-}
Establece el flujo de la imagen.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Establece un valor de cadena que indica el título de la imagen.
