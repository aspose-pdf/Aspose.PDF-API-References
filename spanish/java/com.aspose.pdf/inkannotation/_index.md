---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un \\\"garabato\\\" a mano alzada compuesto por una o más rutas disjuntas."
type: docs
weight: 2430
url: /es/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Representa un \"garabato\" a mano alzada compuesto por una o más rutas disjuntas.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Constructor para la anotación Ink para Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Crea una nueva anotación Ink en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los puntos en InkList, de acuerdo con la transformación de la matriz. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getCapStyle](#getCapStyle--) | Obtiene el estilo de los extremos de línea de la anotación Ink. |
| [getInkList](#getInkList--) | <p> Obtiene la lista de gestos que son líneas independientes representadas por matrices Point[] . </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Establecer estilo de los finales de línea de la anotación de tinta. |
| [setInkList](#setInkList-java.util.List-) | Establece la lista de gestos que son líneas independientes representadas por matrices Point[]. |
| [updateAppearance](#updateAppearance--) | Actualiza la Apariencia, después de que el texto haya sido cambiado/movido. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Constructor para la anotación Ink para Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Crea una nueva anotación Ink en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los puntos en InkList, de acuerdo con la transformación de la matriz.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

Obtiene el estilo de los extremos de línea de la anotación Ink.

**Returns:**
Elemento CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Obtiene la lista de gestos que son líneas independientes representadas por matrices Point[] . </p>

**Returns:**
{@code List<Point[]>} objeto

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Establecer estilo de los finales de línea de la anotación de tinta.

### setInkList {#setInkList-java.util.List-}
Establece la lista de gestos que son líneas independientes representadas por matrices Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Actualiza la Apariencia, después de que el texto haya sido cambiado/movido.
