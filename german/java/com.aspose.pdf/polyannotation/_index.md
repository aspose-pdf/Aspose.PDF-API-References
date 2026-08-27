---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Abstrakte Basisklasse für Poly‑Annotationen."
type: docs
weight: 3890
url: /de/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Abstrakte Basisklasse für Poly‑Annotationen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert die Punkte in Vertices gemäß der Matrixtransformation. |
| [getEndingStyle](#getEndingStyle--) | Liest den Stil des zweiten Linienendes. |
| [getIntent](#getIntent--) | Liest die Absicht der Polygon‑ oder Polylinien‑Anmerkung. |
| [getInteriorColor](#getInteriorColor--) | Liest die Innenfarbe, mit der die Linienenden der Anmerkung gefüllt werden. |
| [getMeasure](#getMeasure--) | Messgrößen, die für diese Anmerkung angegeben sind. |
| [getStartingStyle](#getStartingStyle--) | Liest den Stil des ersten Linienendes. |
| [getVertices](#getVertices--) | Liest ein Array von Punkten, das die horizontalen und vertikalen Koordinaten jedes Scheitelpunkts darstellt. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Setzt den Stil des zweiten Linienendes. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Setzt die Absicht der Polygon‑ oder Polylinien‑Anmerkung. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Setzt die Innenfarbe, mit der die Linienenden der Anmerkung gefüllt werden. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Messgrößen, die für diese Anmerkung angegeben sind. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Setzt den Stil des ersten Linienendes. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Setzt ein Array von Punkten, das die horizontalen und vertikalen Koordinaten jedes Scheitelpunkts darstellt. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert die Punkte in Vertices gemäß der Matrixtransformation.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Liest den Stil des zweiten Linienendes.

**Returns:**
LineEnding-Element @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Liest die Absicht der Polygon‑ oder Polylinien‑Anmerkung.

**Returns:**
PolyIntent-Element @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Liest die Innenfarbe, mit der die Linienenden der Anmerkung gefüllt werden.

**Returns:**
Color-Objekt

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Messgrößen, die für diese Anmerkung angegeben sind.

**Returns:**
Messinstanz

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Liest den Stil des ersten Linienendes.

**Returns:**
LineEnding-Element @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Liest ein Array von Punkten, das die horizontalen und vertikalen Koordinaten jedes Scheitelpunkts darstellt.

**Returns:**
Array von Point-Werten

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Setzt den Stil des zweiten Linienendes.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Setzt die Absicht der Polygon‑ oder Polylinien‑Anmerkung.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Setzt die Innenfarbe, mit der die Linienenden der Anmerkung gefüllt werden.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Messgrößen, die für diese Anmerkung angegeben sind.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Setzt den Stil des ersten Linienendes.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Setzt ein Array von Punkten, das die horizontalen und vertikalen Koordinaten jedes Scheitelpunkts darstellt.
