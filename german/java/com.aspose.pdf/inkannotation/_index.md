---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein freihändiges \\\"Kritzelei\\\" dar, das aus einem oder mehreren getrennten Pfaden besteht."
type: docs
weight: 2430
url: /de/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Stellt eine Freihand‑„Kritzelei“ dar, die aus einem oder mehreren getrennten Pfaden besteht.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Konstruktor für Ink-Annotation für Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Erstellt eine neue Ink-Annotation auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aktualisiert die Punkte in InkList gemäß der Matrixtransformation. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getCapStyle](#getCapStyle--) | Liefert den Stil der Ink-Annotation-Linienenden. |
| [getInkList](#getInkList--) | <p> Ermittelt eine Liste von Gesten, die unabhängige Linien sind und durch Point[]-Arrays dargestellt werden. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Setzt den Stil der Ink-Annotation-Linienenden. |
| [setInkList](#setInkList-java.util.List-) | Setzt die Liste von Gesten, die unabhängige Linien sind und durch Point[]-Arrays dargestellt werden. |
| [updateAppearance](#updateAppearance--) | Aktualisiert das Erscheinungsbild, nachdem der Text geändert/verschoben wurde. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Konstruktor für Ink-Annotation für Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Erstellt eine neue Ink-Annotation auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aktualisiert die Punkte in InkList gemäß der Matrixtransformation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

Liefert den Stil der Ink-Annotation-Linienenden.

**Returns:**
CapStyle-Element @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Ermittelt eine Liste von Gesten, die unabhängige Linien sind und durch Point[]-Arrays dargestellt werden. </p>

**Returns:**
{@code List<Point[]>}-Objekt

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Setzt den Stil der Ink-Annotation-Linienenden.

### setInkList {#setInkList-java.util.List-}
Setzt die Liste von Gesten, die unabhängige Linien sind und durch Point[]-Arrays dargestellt werden.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Aktualisiert das Erscheinungsbild, nachdem der Text geändert/verschoben wurde.
