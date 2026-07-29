---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase base abstracta para poly-annotations."
type: docs
weight: 3890
url: /es/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Clase base abstracta para poly-annotations.

## Métodos

| Método | Descripción |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los puntos en Vertices, de acuerdo con la transformación de la matriz. |
| [getEndingStyle](#getEndingStyle--) | Obtiene el estilo del extremo de la segunda línea. |
| [getIntent](#getIntent--) | Obtiene la intención de la anotación de polígono o polilínea. |
| [getInteriorColor](#getInteriorColor--) | Obtiene el color interior con el que rellenar los extremos de línea de la anotación. |
| [getMeasure](#getMeasure--) | Unidades de medida especificadas para esta anotación. |
| [getStartingStyle](#getStartingStyle--) | Obtiene el estilo del extremo de la primera línea. |
| [getVertices](#getVertices--) | Obtiene una matriz de puntos que representan las coordenadas horizontales y verticales de cada vértice. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Establece el estilo del extremo de la segunda línea. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Establece la intención de la anotación de polígono o polilínea. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Establece el color interior con el que rellenar los extremos de línea de la anotación. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unidades de medida especificadas para esta anotación. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Establece el estilo del extremo de la primera línea. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Establece una matriz de puntos que representan las coordenadas horizontales y verticales de cada vértice. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los puntos en Vertices, de acuerdo con la transformación de la matriz.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtiene el estilo del extremo de la segunda línea.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Obtiene la intención de la anotación de polígono o polilínea.

**Returns:**
Elemento PolyIntent @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtiene el color interior con el que rellenar los extremos de línea de la anotación.

**Returns:**
Objeto Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unidades de medida especificadas para esta anotación.

**Returns:**
Instancia Measure

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtiene el estilo del extremo de la primera línea.

**Returns:**
Elemento LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Obtiene una matriz de puntos que representan las coordenadas horizontales y verticales de cada vértice.

**Returns:**
matriz de valores Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Establece el estilo del extremo de la segunda línea.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Establece la intención de la anotación de polígono o polilínea.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Establece el color interior con el que rellenar los extremos de línea de la anotación.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unidades de medida especificadas para esta anotación.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Establece el estilo del extremo de la primera línea.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Establece una matriz de puntos que representan las coordenadas horizontales y verticales de cada vértice.
