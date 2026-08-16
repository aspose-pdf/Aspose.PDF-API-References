---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de {@code."
type: docs
weight: 2340
url: /es/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de la colección {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> El ejemplo muestra cómo encontrar imágenes en la primera página del documento PDF y obtener las propiedades de colocación de la imagen. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crear objeto ImagePlacementAbsorber para realizar la búsqueda de colocación de imágenes ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Aceptar el absorbente para la primera página doc.getPages().get_Item(1).accept(abs); // Mostrar propiedades de colocación de imágenes para todas las colocaciones for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> El objeto {@code ImagePlacementAbsorber} se utiliza básicamente en escenarios de búsqueda de imágenes. Cuando la búsqueda se completa, las ocurrencias se representan con objetos {@code ImagePlacement} que contiene la colección {@code ImagePlacementAbsorber.ImagePlacements}. El objeto {@code ImagePlacement} proporciona acceso a las propiedades de colocación de la imagen: dimensiones, resolución, etc. </p> La rotación positiva de la imagen es en sentido antihorario; para la página, es en sentido horario. Aquí, necesitamos representar el ángulo de rotación de la imagen, por lo que restamos el ángulo de la página del ángulo de la imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Inicializa una nueva instancia del objeto {@code ImagePlacementAbsorber}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Obtiene la colección de ocurrencias de colocación de imágenes que se presentan con objetos {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Realiza una búsqueda en el documento especificado. |
| [visit](#visit-com.aspose.pdf.Page-) | Realiza la búsqueda en la página especificada. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Inicializa una nueva instancia del objeto {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Obtiene la colección de ocurrencias de colocación de imágenes que se presentan con objetos {@code ImagePlacement}.

**Returns:**
Objeto ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria.

**Returns:**
valor booleano

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
Realiza una búsqueda en el documento especificado.

### visit {#visit-com.aspose.pdf.Page-}
Realiza la búsqueda en la página especificada.
