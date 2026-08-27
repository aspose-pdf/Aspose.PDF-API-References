---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Redact-Anmerkung dar."
type: docs
weight: 4120
url: /de/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Stellt eine Redact-Anmerkung dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Konstruktor für RedactionAnnotation. Zur Verwendung im Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor für RedactAnnotation. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [flatten](#flatten--) | Flacht die Annotation ab, d. h. entfernt die Annotation und fügt ihren Inhalt hinzu |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getBorderColor](#getBorderColor--) | Liefert die Farbe des Rahmens, die gezeichnet wird, wenn Redaction nicht aktiv ist. |
| [getDefaultAppearance](#getDefaultAppearance--) | Liefert oder setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird. |
| [getFillColor](#getFillColor--) | Liefert die Farbe zum Ausfüllen der Annotation. |
| [getFontSize](#getFontSize--) | Liefert die Schriftgröße für OverlayText. |
| [getOverlayText](#getOverlayText--) | Liefert den Text, der auf der RedactAnnotation gedruckt wird. |
| [getQuadPoint](#getQuadPoint--) | Ein Array von 8×N Zahlen, das die Koordinaten des Inhaltsbereichs angibt, der entfernt werden soll. |
| [getQuadPoints](#getQuadPoints--) | Liest ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text. |
| [getTextAlignment](#getTextAlignment--) | Liefert die Ausrichtung des Overlay‑Textes. |
| [isRepeat](#isRepeat--) | Wenn true, wird der Overlay‑Text auf der Annotation wiederholt. |
| [redact](#redact--) | Flacht die Annotation ab und redigiert Seiteninhalte (d. h. entfernt Text- und Bildinhalt unter redacted annotation) |
| [redactExact](#redactExact--) | Flacht die Annotation ab und redigiert Seiteninhalte (d. h. entfernt Text- und Bildinhalt exakt unter redacted annotation) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Legt die Farbe des Rahmens fest, der gezeichnet wird, wenn die Redaktion nicht aktiv ist. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Liefert oder setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Legt die Farbe zum Ausfüllen der Anmerkung fest. |
| [setFontSize](#setFontSize-float-) | Legt die Schriftgröße für OverlayText fest. Standardwert ist 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Legt den Text fest, der auf der Redaktions-Anmerkung gedruckt wird. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Ein Array von 8×N Zahlen, das die Koordinaten des Inhaltsbereichs angibt, der entfernt werden soll. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Setzt ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text. |
| [setRepeat](#setRepeat-boolean-) | Wenn true, wird der Overlay‑Text auf der Annotation wiederholt. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Legt die Ausrichtung des Overlay-Textes fest. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Konstruktor für RedactionAnnotation. Zur Verwendung im Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor für RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### flatten {#flatten--}
```
public void flatten()
```

Flacht die Annotation ab, d. h. entfernt die Annotation und fügt ihren Inhalt hinzu

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Liefert die Farbe des Rahmens, die gezeichnet wird, wenn Redaction nicht aktiv ist.

**Returns:**
Farbwert

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Liefert oder setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird.

**Returns:**
String Wert

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Liefert die Farbe zum Ausfüllen der Annotation.

**Returns:**
Farbwert

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Liefert die Schriftgröße für OverlayText.

**Returns:**
int-Wert

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Liefert den Text, der auf der RedactAnnotation gedruckt wird.

**Returns:**
String-Wert

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Ein Array von 8×N Zahlen, das die Koordinaten des Inhaltsbereichs angibt, der entfernt werden soll.

**Returns:**
Array von Punkten

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Liest ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text.

**Returns:**
Array von Point-Werten

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Liefert die Ausrichtung des Overlay‑Textes.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Wenn true, wird der Overlay‑Text auf der Annotation wiederholt.

**Returns:**
boolescher Wert

### redact {#redact--}
```
public void redact()
```

Flacht die Annotation ab und redigiert Seiteninhalte (d. h. entfernt Text- und Bildinhalt unter redacted annotation)

### redactExact {#redactExact--}
```
public void redactExact()
```

Flacht die Annotation ab und redigiert Seiteninhalte (d. h. entfernt Text- und Bildinhalt exakt unter redacted annotation)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Legt die Farbe des Rahmens fest, der gezeichnet wird, wenn die Redaktion nicht aktiv ist.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Liefert oder setzt die Standard‑Darstellungszeichenfolge, die beim Formatieren des Textes verwendet wird.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Legt die Farbe zum Ausfüllen der Anmerkung fest.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Legt die Schriftgröße für OverlayText fest. Standardwert ist 10.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSize |  | int-Wert |

### setOverlayText {#setOverlayText-java.lang.String-}
Legt den Text fest, der auf der Redaktions-Anmerkung gedruckt wird.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Ein Array von 8×N Zahlen, das die Koordinaten des Inhaltsbereichs angibt, der entfernt werden soll.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Setzt ein Array von Punkten, das die Koordinaten von n Quadrilateralen angibt. Jeder Quadrilateral umfasst ein Wort oder eine Gruppe zusammenhängender Wörter im dem der Annotation zugrunde liegenden Text.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Wenn true, wird der Overlay‑Text auf der Annotation wiederholt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Legt die Ausrichtung des Overlay-Textes fest.
