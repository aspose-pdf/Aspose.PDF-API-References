---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine Caret-Anmerkung darstellt."
type: docs
weight: 470
url: /de/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Klasse, die eine Caret-Anmerkung darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Konstruktor für die Verwendung im Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstellt eine neue Caret‑Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getFrame](#getFrame--) | Ruft das Caret‑Rechteck ab. |
| [getSymbol](#getSymbol--) | Ruft das mit dem Caret verbundene Symbol ab. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Setzt das Caret‑Rechteck. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Legt die Ausgabeseitengröße für den Import fest. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Konstruktor für die Verwendung im Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstellt eine neue Caret‑Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType‑Element

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Ruft das Caret‑Rechteck ab.

**Returns:**
Caret‑Rechteck.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Ruft das mit dem Caret verbundene Symbol ab. {@code CaretSymbol}

**Returns:**
CaretSymbol‑Element @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Setzt das Caret‑Rechteck.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Legt die Ausgabeseitengröße für den Import fest.
