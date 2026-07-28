---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase PDF3DAnnotation. Esta clase no puede heredarse. @see Annotation"
type: docs
weight: 3560
url: /es/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Clase PDF3DAnnotation. Esta clase no puede heredarse. @see Annotation

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Inicializa una nueva instancia de la clase {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Inicializa una nueva instancia de la clase {@code PDF3DAnnotation}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta visitante para el procesamiento de anotaciones. |
| [clearImagePreview](#clearImagePreview--) | Borra la vista previa de la imagen. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. Valor: El tipo de la anotación. |
| [getContent](#getContent--) | Obtiene o establece el contenido. Valor: El contenido. |
| [getImagePreview](#getImagePreview--) | Obtiene la vista previa de la imagen. |
| [getLightingScheme](#getLightingScheme--) | Obtiene el esquema de iluminación. Valor: El esquema de iluminación. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Obtiene la obra de arte 3D. Valor: La obra de arte PDF3 d. |
| [getRenderMode](#getRenderMode--) | Obtiene el modo de renderizado. Valor: El modo de renderizado. |
| [getViewArray](#getViewArray--) | Obtiene la matriz de vistas. Valor: La matriz de vistas. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Obtiene o establece el contenido. Valor: El contenido. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Establece el índice de la vista predeterminada. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Establece la vista previa de la imagen. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Establece la vista previa de la imagen. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Inicializa una nueva instancia de la clase {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Inicializa una nueva instancia de la clase {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta visitante para el procesamiento de anotaciones.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Borra la vista previa de la imagen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación. Valor: El tipo de la anotación.

**Returns:**
valor int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Obtiene o establece el contenido. Valor: El contenido.

**Returns:**
PDF3DContent object

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Obtiene la vista previa de la imagen.

**Returns:**
Vista previa de la imagen como flujo.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Obtiene el esquema de iluminación. Valor: El esquema de iluminación.

**Returns:**
PDF3DLightingScheme object

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Obtiene la obra de arte 3D. Valor: La obra de arte PDF3 d.

**Returns:**
objeto PDF3DArtwork

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Obtiene el modo de renderizado. Valor: El modo de renderizado.

**Returns:**
objeto PDF3DRenderMode

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Obtiene la matriz de vistas. Valor: La matriz de vistas.

**Returns:**
objeto PDF3DViewArray

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Obtiene o establece el contenido. Valor: El contenido.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Establece el índice de la vista predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice de vista predeterminado. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Establece la vista previa de la imagen.

### setImagePreview {#setImagePreview-java.lang.String-}
Establece la vista previa de la imagen.
