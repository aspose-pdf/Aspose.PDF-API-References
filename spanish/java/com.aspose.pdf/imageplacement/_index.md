---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa características de una imagen colocada en una página de documento Pdf. </p> <hr> <pre> El ejemplo muestra cómo encontrar imágenes en la primera página del documento PDF y obtener imágenes.</pre>"
type: docs
weight: 2330
url: /es/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Representa características de una imagen colocada en una página de documento Pdf. </p> <hr> <pre> El ejemplo muestra cómo encontrar imágenes en la primera página del documento PDF y obtener imágenes como mapas de bits con dimensiones visibles. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crear objeto ImagePlacementAbsorber para realizar la búsqueda de colocación de imágenes ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Aceptar el absorbente para la primera página doc.getPages().get_Item(1).accept(abs); // Recuperar imágenes con dimensiones visibles for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Recuperar imagen de los recursos imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Crear nuevo mapa de bits con dimensiones reales scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Cuando una imagen se coloca en una página puede tener dimensiones diferentes a las dimensiones físicas definidas en {@code Resources}. El objeto {@code ImagePlacement} está destinado a proporcionar dicha información como dimensiones, resolución, etc. </p>

## Métodos

| Método | Descripción |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Obtiene los parámetros de composición del estado gráfico activo para la imagen colocada en la página. |
| [getImage](#getImage--) | Obtiene el objeto de recurso XImage relacionado. |
| [getMatrix](#getMatrix--) | Matriz de transformación actual para esta imagen. |
| [getOperator](#getOperator--) | Operador utilizado para mostrar la imagen. |
| [getPage](#getPage--) | Obtiene la página que contiene la imagen. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo de la Imagen. |
| [getResolution](#getResolution--) | Obtiene la resolución de la Imagen. |
| [getRotation](#getRotation--) | Obtiene el ángulo de rotación de la Imagen. |
| [hide](#hide--) | Eliminar imagen de la página. |
| [replace](#replace-java.io.InputStream-) | Reemplazar la imagen en la colección con otra imagen. |
| [save](#save-java.io.OutputStream-) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Obtiene los parámetros de composición del estado gráfico activo para la imagen colocada en la página.

**Returns:**
Objeto CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

Obtiene el objeto de recurso XImage relacionado.

**Returns:**
objeto XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matriz de transformación actual para esta imagen.

**Returns:**
Objeto Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operador utilizado para mostrar la imagen.

**Returns:**
Instancia de Operator

### getPage {#getPage--}
```
public Page getPage()
```

Obtiene la página que contiene la imagen.

**Returns:**
objeto Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo de la Imagen.

**Returns:**
objeto Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtiene la resolución de la Imagen.

**Returns:**
Objeto Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtiene el ángulo de rotación de la Imagen.

**Returns:**
valor int

### hide {#hide--}
```
public final void hide()
```

Eliminar imagen de la página.

### replace {#replace-java.io.InputStream-}
Reemplazar la imagen en la colección con otra imagen.

### save {#save-java.io.OutputStream-}
Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución.
