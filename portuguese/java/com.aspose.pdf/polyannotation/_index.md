---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe base abstrata para poly‑annotations."
type: docs
weight: 3890
url: /pt/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Classe base abstrata para poly‑annotations.

## Métodos

| Método | Descrição |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza os pontos em Vertices, de acordo com a transformação da matriz. |
| [getEndingStyle](#getEndingStyle--) | Obtém o estilo da terminação da segunda linha. |
| [getIntent](#getIntent--) | Obtém a intenção da anotação de polígono ou polilinha. |
| [getInteriorColor](#getInteriorColor--) | Obtém a cor interna usada para preencher as terminações de linha da anotação. |
| [getMeasure](#getMeasure--) | Unidades de medida especificadas para esta anotação. |
| [getStartingStyle](#getStartingStyle--) | Obtém o estilo da terminação da primeira linha. |
| [getVertices](#getVertices--) | Obtém um array de pontos que representam as coordenadas horizontais e verticais de cada vértice. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Define o estilo da terminação da segunda linha. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Define a intenção da anotação de polígono ou polilinha. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Define a cor interna usada para preencher as terminações de linha da anotação. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unidades de medida especificadas para esta anotação. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Define o estilo da terminação da primeira linha. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Define um array de pontos que representam as coordenadas horizontais e verticais de cada vértice. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza os pontos em Vertices, de acordo com a transformação da matriz.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtém o estilo da terminação da segunda linha.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Obtém a intenção da anotação de polígono ou polilinha.

**Returns:**
PolyIntent elemento @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtém a cor interna usada para preencher as terminações de linha da anotação.

**Returns:**
Objeto Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unidades de medida especificadas para esta anotação.

**Returns:**
Instância de Medição

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtém o estilo da terminação da primeira linha.

**Returns:**
Elemento LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Obtém um array de pontos que representam as coordenadas horizontais e verticais de cada vértice.

**Returns:**
array de valores Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Define o estilo da terminação da segunda linha.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Define a intenção da anotação de polígono ou polilinha.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Define a cor interna usada para preencher as terminações de linha da anotação.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unidades de medida especificadas para esta anotação.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Define o estilo da terminação da primeira linha.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Define um array de pontos que representam as coordenadas horizontais e verticais de cada vértice.
