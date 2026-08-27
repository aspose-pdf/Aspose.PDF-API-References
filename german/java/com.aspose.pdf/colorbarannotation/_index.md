---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die die ColorBarAnnotation-Annotation darstellt. Eigenschaft Color ignoriert, stattdessen wird die ColorsOfCMYK-Farbe verwendet. Bei der Erstellung bestimmt das Verhältnis von Breite zu Höhe die Ausrichtung."
type: docs
weight: 680
url: /de/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Klasse, die die ColorBarAnnotation‑Annotation darstellt. Die Eigenschaft Color wird ignoriert, stattdessen wird die ColorsOfCMYK‑Farbe verwendet. Bei der Erstellung bestimmt das Verhältnis von Breite und Höhe die Ausrichtung der Annotation – horizontal oder vertikal. Anschließend wird geprüft, ob das Annotationsrechteck außerhalb des TrimBox liegt; falls nicht, wird es an die nächstgelegene Position außerhalb des TrimBox verschoben, wobei die Ausrichtung der Annotation berücksichtigt wird. Es ist möglich, die Breite (Höhe) zu reduzieren, damit die Annotation außerhalb des TrimBox passt. Gibt es keinen Platz für das Layout, können Breite/Höhe auf Null gesetzt werden (in diesem Fall ist die Annotation auf der Seite vorhanden, wird jedoch nicht angezeigt).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstellt eine neue ColorBar-Annotation auf der angegebenen Seite. Standard: ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Erstellt eine neue ColorBar-annotation auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert Parameter und Darstellung gemäß der Matrixtransformation und dem Verschieben außerhalb des TrimBox, falls erforderlich. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getColorOfCMYK](#getColorOfCMYK--) | Liest oder setzt die Farbe (eine von Cyan, Magenta, Gelb, Schwarz), für die die Annotation gezeichnet wird. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Liest oder setzt die Farbe (eine von Cyan, Magenta, Gelb, Schwarz), für die die Annotation gezeichnet wird. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstellt eine neue ColorBar-Annotation auf der angegebenen Seite. Standard: ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Erstellt eine neue ColorBar-annotation auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert Parameter und Darstellung gemäß der Matrixtransformation und dem Verschieben außerhalb des TrimBox, falls erforderlich.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
int-Wert

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Liest oder setzt die Farbe (eine von Cyan, Magenta, Gelb, Schwarz), für die die Annotation gezeichnet wird.

**Returns:**
ColorsOfCMYK-Element

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Liest oder setzt die Farbe (eine von Cyan, Magenta, Gelb, Schwarz), für die die Annotation gezeichnet wird.
