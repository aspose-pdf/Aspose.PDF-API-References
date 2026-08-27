---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt ein Push‑Button‑Feld dar."
type: docs
weight: 440
url: /de/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Klasse stellt ein Push‑Button‑Feld dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ButtonField](#ButtonField--) | Button‑Feld‑Konstruktor für Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Button‑Feld‑Konstruktor für Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Button‑Feld‑Konstruktor für Generator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Fügt ein Bild in die Feldressourcen ein und zeichnet es. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Fügt ein Bild in die Feldressourcen ein und zeichnet es. |
| [getAlternateCaption](#getAlternateCaption--) | Ruft die alternative Beschriftung der Schaltfläche ab, die angezeigt wird, wenn die Maustaste innerhalb ihres aktiven Bereichs gedrückt wird. |
| [getAlternateIcon](#getAlternateIcon--) | Ruft das alternative Symbol ab, das angezeigt wird, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird. |
| [getIconFit](#getIconFit--) | Ruft das IconFit-Objekt ab, das festlegt, wie das Symbol der Widget-Anmerkung innerhalb ihres Anmerkungsrechtecks angezeigt wird. |
| [getICPosition](#getICPosition--) | Ruft die Position der Symbolbeschriftung ab. |
| [getNormalCaption](#getNormalCaption--) | Ruft die normale Beschriftung ab. |
| [getNormalIcon](#getNormalIcon--) | Ruft das normale Symbol der Schaltfläche ab, das angezeigt wird, wenn keine Interaktion mit dem Benutzer stattfindet. |
| [getRolloverCaption](#getRolloverCaption--) | Ruft die Roll-over-Beschriftung der Schaltfläche ab, die angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |
| [getRolloverIcon](#getRolloverIcon--) | Ruft das Roll-over-Symbol der Schaltfläche ab, das angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Setzt die alternative Beschriftung der Schaltfläche, die angezeigt wird, wenn die Maustaste innerhalb ihres aktiven Bereichs gedrückt wird. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Setzt das alternative Symbol, das angezeigt wird, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Setzt die Position der Symbolbeschriftung. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Setzt die normale Beschriftung. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Setzt das normale Symbol der Schaltfläche, das angezeigt wird, wenn keine Interaktion mit dem Benutzer stattfindet. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Setzt die Roll-over-Beschriftung der Schaltfläche, die angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Setzt das Roll-over-Symbol der Schaltfläche, das angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Button‑Feld‑Konstruktor für Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Button‑Feld‑Konstruktor für Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Button‑Feld‑Konstruktor für Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Fügt ein Bild in die Feldressourcen ein und zeichnet es.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Fügt ein Bild in die Feldressourcen ein und zeichnet es.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Ruft die alternative Beschriftung der Schaltfläche ab, die angezeigt wird, wenn die Maustaste innerhalb ihres aktiven Bereichs gedrückt wird.

**Returns:**
String Wert

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Ruft das alternative Symbol ab, das angezeigt wird, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird.

**Returns:**
XForm-Objekt

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Ruft das IconFit-Objekt ab, das festlegt, wie das Symbol der Widget-Anmerkung innerhalb ihres Anmerkungsrechtecks angezeigt wird.

**Returns:**
IconFit-Objekt

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Ruft die Position der Symbolbeschriftung ab.

**Returns:**
Symbolbeschriftungsposition. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Ruft die normale Beschriftung ab.

**Returns:**
String Wert

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Ruft das normale Symbol der Schaltfläche ab, das angezeigt wird, wenn keine Interaktion mit dem Benutzer stattfindet.

**Returns:**
XForm-Objekt

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Ruft die Roll-over-Beschriftung der Schaltfläche ab, die angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken.

**Returns:**
String Wert

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Ruft das Roll-over-Symbol der Schaltfläche ab, das angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken.

**Returns:**
XForm-Objekt

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Setzt die alternative Beschriftung der Schaltfläche, die angezeigt wird, wenn die Maustaste innerhalb ihres aktiven Bereichs gedrückt wird.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Setzt das alternative Symbol, das angezeigt wird, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt wird.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Setzt die Position der Symbolbeschriftung.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Setzt die normale Beschriftung.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Setzt das normale Symbol der Schaltfläche, das angezeigt wird, wenn keine Interaktion mit dem Benutzer stattfindet.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Setzt die Roll-over-Beschriftung der Schaltfläche, die angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Setzt das Roll-over-Symbol der Schaltfläche, das angezeigt wird, wenn der Benutzer den Zeiger in den aktiven Bereich bewegt, ohne die Maustaste zu drücken.
