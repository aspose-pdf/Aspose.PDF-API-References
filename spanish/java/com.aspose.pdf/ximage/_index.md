---
title: "XImage"
linktitle: "XImage"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el objeto de imagen X-Object."
type: docs
weight: 5610
url: /es/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Clase que representa el objeto de imagen X-Object.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | solo para uso interno |

## Métodos

| Método | Descripción |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Agrega una máscara de plantilla al XImage. |
| [containsTransparency](#containsTransparency--) | Si la imagen contiene transparencia entonces devuelve true; de lo contrario, false. |
| [delete](#delete--) | Elimina la imagen de la colección principal. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Devuelve el tipo de color de la imagen. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Devuelve una lista de cadenas con Texto Alternativo para un XImage. |
| [getColorType](#getColorType--) | Devuelve el tipo de color de la imagen. |
| [getEngineImg](#getEngineImg--) | Objeto IPdfImage que describe la imagen. Solo interno |
| [getFilterType](#getFilterType--) | Obtiene el tipo de filtro de la imagen. |
| [getGrayscaled](#getGrayscaled--) | Obtiene la versión en escala de grises de la imagen. |
| [getHeight](#getHeight--) | Obtiene la altura de la imagen. |
| [getImage](#getImage--) | Solo para uso interno |
| [getMetadata](#getMetadata--) | Metadatos de la imagen. |
| [getName](#getName--) | Obtiene el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método XImage.Rename en este caso. |
| [getNameInCollection](#getNameInCollection--) | Devuelve el nombre de la imagen en su colección. |
| [getRawBytes](#getRawBytes--) | Devuelve los bytes sin procesar de la imagen sin decodificar. |
| [getRawImageData](#getRawImageData--) | Obtiene los datos sin procesar de la imagen desde la imagen de origen. |
| [getRawParameters](#getRawParameters--) | Obtiene los parámetros sin procesar de la imagen |
| [getWidth](#getWidth--) | Obtiene el ancho de la imagen. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Devuelve true si la primitiva es una imagen. |
| [isImageMask](#isImageMask--) | Obtiene una bandera que indica si la imagen debe tratarse como una máscara de imagen (ver 8.9.6, "Masked Images"). Si esta bandera es true, el valor de BitsPerComponent debe ser 1 y no deben especificarse Mask y ColorSpace; las áreas sin máscara deben pintarse usando el color de trazo actual. Valor predeterminado: false. Valor: True si la imagen es una máscara de imagen. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Devuelve true si ambas imágenes hacen referencia al mismo objeto. |
| [rename](#rename-java.lang.String-) | Renombra la imagen y reemplaza todas las referencias a la imagen con el nuevo nombre |
| [replace](#replace-java.io.InputStream-) | Reemplaza la imagen en el flujo especificado en {@code image}. * |
| [save](#save-java.io.OutputStream-) | Guarda los datos de la imagen en el flujo como una imagen JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | Guarda la imagen en el flujo con el formato solicitado. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Guarda la imagen en el flujo con el formato solicitado. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Guarda la imagen en el flujo con el formato solicitado. |
| [save](#save-java.io.OutputStream-int-) | Guarda la imagen en el flujo con el formato solicitado y la resolución especificada. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Guarda la imagen en el flujo con el formato solicitado. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Guarda los datos de la imagen en el flujo como una imagen JPEG con la resolución especificada. |
| [setName](#setName-java.lang.String-) | Establece el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método XImage.Rename en este caso. |
| [toStream](#toStream--) | Devuelve el flujo original de la imagen. |
| [toString](#toString--) | Devuelve una representación en cadena de las propiedades del objeto XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Establece el texto alternativo para un XImage en la página. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
solo para uso interno

### addStencilMask {#addStencilMask-java.io.InputStream-}
Agrega una máscara de plantilla al XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Si la imagen contiene transparencia entonces devuelve true; de lo contrario, false.

**Returns:**
valor booleano

### delete {#delete--}
```
public void delete()
```

Elimina la imagen de la colección principal.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Devuelve el tipo de color de la imagen.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Devuelve una lista de cadenas con Texto Alternativo para un XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Devuelve el tipo de color de la imagen.

**Returns:**
El valor del tipo de color.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

Objeto IPdfImage que describe la imagen. Solo interno

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Obtiene el tipo de filtro de la imagen.

**Returns:**
Elemento ImageFilterType

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Obtiene la versión en escala de grises de la imagen.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtiene la altura de la imagen.

**Returns:**
valor int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Solo para uso interno

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadatos de la imagen.

**Returns:**
Instancia de Metadata

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método XImage.Rename en este caso.

**Returns:**
Cadena

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Devuelve el nombre de la imagen en su colección.

**Returns:**
Clave de imagen (nombre).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Devuelve los bytes sin procesar de la imagen sin decodificar.

**Returns:**
matriz de bytes

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Obtiene los datos sin procesar de la imagen desde la imagen de origen.

**Returns:**
Un {@link byte[]} que contiene los datos originales de la imagen.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Obtiene los parámetros sin procesar de la imagen

**Returns:**
Instancia de RawParameters

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtiene el ancho de la imagen.

**Returns:**
valor int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Devuelve true si la primitiva es una imagen.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Obtiene una bandera que indica si la imagen debe tratarse como una máscara de imagen (ver 8.9.6, "Masked Images"). Si esta bandera es true, el valor de BitsPerComponent debe ser 1 y no deben especificarse Mask y ColorSpace; las áreas sin máscara deben pintarse usando el color de trazo actual. Valor predeterminado: false. Valor: True si la imagen es una máscara de imagen.

**Returns:**
valor booleano

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Devuelve true si ambas imágenes hacen referencia al mismo objeto.

### rename {#rename-java.lang.String-}
Renombra la imagen y reemplaza todas las referencias a la imagen con el nuevo nombre

### replace {#replace-java.io.InputStream-}
Reemplaza la imagen en el flujo especificado en {@code image}. *

### save {#save-java.io.OutputStream-}
Guarda los datos de la imagen en el flujo como una imagen JPEG.

### save {#save-java.io.OutputStream-float-float-}
Guarda la imagen en el flujo con el formato solicitado.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Guarda la imagen en el flujo con el formato solicitado.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Guarda la imagen en el flujo con el formato solicitado.

### save {#save-java.io.OutputStream-int-}
Guarda la imagen en el flujo con el formato solicitado y la resolución especificada.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Guarda la imagen en el flujo con el formato solicitado.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Guarda los datos de la imagen en el flujo como una imagen JPEG con la resolución especificada.

### setName {#setName-java.lang.String-}
Establece el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método XImage.Rename en este caso.

### toStream {#toStream--}
```
public InputStream toStream()
```

Devuelve el flujo original de la imagen.

**Returns:**
El flujo de imagen original.

### toString {#toString--}
```
public String toString()
```

Devuelve una representación en cadena de las propiedades del objeto XImage.

**Returns:**
Instancia de String

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Establece el texto alternativo para un XImage en la página.
