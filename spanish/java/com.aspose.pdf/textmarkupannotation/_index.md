---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase base abstracta para anotaciones de marcado de texto."
type: docs
weight: 5180
url: /es/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Clase base abstracta para anotaciones de marcado de texto.

## Métodos

| Método | Descripción |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los QuadPoints, de acuerdo con la transformación de la matriz. |
| [getMarkedText](#getMarkedText--) | Obtiene el texto bajo la anotación de marcado como cadena. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Obtiene el texto bajo la anotación de marcado como {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Obtiene una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Establece una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los QuadPoints, de acuerdo con la transformación de la matriz.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Obtiene el texto bajo la anotación de marcado como cadena.

**Returns:**
Cadena que contiene el texto que está bajo la anotación de marcado.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Obtiene el texto bajo la anotación de marcado como {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} que contiene {@code TextFragment}s que están bajo la anotación de marcado.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Obtiene una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación.

**Returns:**
matriz de valores Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Establece una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación.
