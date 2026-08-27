---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine Linienannotation darstellt."
type: docs
weight: 2710
url: /de/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Klasse, die eine Linienannotation darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Konstruktor zur Verwendung mit Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Erstellt eine neue Linienannotation auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert einen Besucher zur Annotationsverarbeitung. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert die Start- und Endpunkte gemäß der Matrixtransformation. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getCaptionOffset](#getCaptionOffset--) | Ermittelt den Versatz des Beschriftungstextes von seiner normalen Position. |
| [getCaptionPosition](#getCaptionPosition--) | Ermittelt die Position der Annotationsbeschriftung. |
| [getEnding](#getEnding--) | Ermittelt den Endpunkt der Linie. |
| [getEndingStyle](#getEndingStyle--) | Ermittelt den Endstil für den Endpunkt der Linie. |
| [getIntent](#getIntent--) | Ermittelt die Absicht der Linienannotation. |
| [getInteriorColor](#getInteriorColor--) | Ermittelt die Innenfarbe der Annotation. |
| [getLeaderLine](#getLeaderLine--) | Ermittelt die Länge der Leitlinie. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Ermittelt die Länge der Erweiterung der Leitlinie. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Ermittelt den Versatz der Leitlinie. |
| [getMeasure](#getMeasure--) | Messgrößen, die für diese Annotation angegeben sind. |
| [getShowCaption](#getShowCaption--) | Ermittelt das boolesche Flag, das bestimmt, ob Inhalte als Beschriftung angezeigt werden müssen. |
| [getStarting](#getStarting--) | Ermittelt den Startpunkt der Linie. |
| [getStartingStyle](#getStartingStyle--) | Ermittelt den Endstil der Linie für den Startpunkt. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Setzt den Versatz des Beschriftungstextes von seiner normalen Position. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Setzt die Position der Annotationsbeschriftung. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Setzt den Endpunkt der Linie. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Setzt den Endstil für den Endpunkt der Linie. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Setzt die Absicht der Linienannotation. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Setzt die Innenfarbe der Annotation. |
| [setLeaderLine](#setLeaderLine-double-) | Legt die Länge der Führungslinie fest. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Legt die Länge der Erweiterung der Führungslinie fest. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Legt den Versatz der Führungslinie fest. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Messgrößen, die für diese Annotation angegeben sind. |
| [setShowCaption](#setShowCaption-boolean-) | Setzt das boolesche Flag, das bestimmt, ob Inhalte als Beschriftung angezeigt werden müssen. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Legt den Startpunkt der Linie fest. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Legt den Linienendstil für den Startpunkt der Linie fest. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Konstruktor zur Verwendung mit Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Erstellt eine neue Linienannotation auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert einen Besucher zur Annotationsverarbeitung.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert die Start- und Endpunkte gemäß der Matrixtransformation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Ermittelt den Versatz des Beschriftungstextes von seiner normalen Position.

**Returns:**
Point-Objekt

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Ermittelt die Position der Annotationsbeschriftung.

**Returns:**
CaptionPosition-Element @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Ermittelt den Endpunkt der Linie.

**Returns:**
Punktwert

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Ermittelt den Endstil für den Endpunkt der Linie.

**Returns:**
LineEnding-Element @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Ermittelt die Absicht der Linienannotation.

**Returns:**
LineIntent-Element @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Ermittelt die Innenfarbe der Annotation.

**Returns:**
Color-Objekt

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Ermittelt die Länge der Leitlinie.

**Returns:**
double-Wert

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Ermittelt die Länge der Erweiterung der Leitlinie.

**Returns:**
double-Wert

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Ermittelt den Versatz der Leitlinie.

**Returns:**
double-Wert

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Messgrößen, die für diese Annotation angegeben sind.

**Returns:**
Measure-Objekt

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Ermittelt das boolesche Flag, das bestimmt, ob Inhalte als Beschriftung angezeigt werden müssen.

**Returns:**
boolescher Wert

### getStarting {#getStarting--}
```
public Point getStarting()
```

Ermittelt den Startpunkt der Linie.

**Returns:**
Punktwert

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Ermittelt den Endstil der Linie für den Startpunkt.

**Returns:**
LineEnding-Element @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Setzt den Versatz des Beschriftungstextes von seiner normalen Position.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Setzt die Position der Annotationsbeschriftung.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Setzt den Endpunkt der Linie.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Setzt den Endstil für den Endpunkt der Linie.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Setzt die Absicht der Linienannotation.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Setzt die Innenfarbe der Annotation.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Legt die Länge der Führungslinie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Legt die Länge der Erweiterung der Führungslinie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Legt den Versatz der Führungslinie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Messgrößen, die für diese Annotation angegeben sind.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Setzt das boolesche Flag, das bestimmt, ob Inhalte als Beschriftung angezeigt werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Legt den Startpunkt der Linie fest.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Legt den Linienendstil für den Startpunkt der Linie fest.
