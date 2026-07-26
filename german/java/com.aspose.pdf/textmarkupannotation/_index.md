---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Abstrakte Basisklasse für Text-Markup-Annotationen."
type: docs
weight: 5180
url: /de/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Abstrakte Basisklasse für Text-Markup-Annotationen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert die QuadPoints gemäß der Matrixtransformation. |
| [getMarkedText](#getMarkedText--) | Liest den Text unter der Markup-Annotation als Zeichenkette. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Liest den Text unter der Markup-Annotation als {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Liest ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Setzt ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert die QuadPoints gemäß der Matrixtransformation.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Liest den Text unter der Markup-Annotation als Zeichenkette.

**Returns:**
Zeichenkette, die den Text enthält, der sich unter der Markup-Annotation befindet.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Liest den Text unter der Markup-Annotation als {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} enthält {@code TextFragment}s, die sich unter Markup-Annotation befinden.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Liest ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text.

**Returns:**
Array von Point-Werten

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Setzt ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text.
