---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt entweder einen Hyperlink zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar."
type: docs
weight: 2760
url: /de/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Stellt entweder einen Hyperlink zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstellt eine neue Link-Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAction](#getAction--) | Ruft eine Aktion ab, die ausgeführt werden soll, wenn die Link-Anmerkung aktiviert wird. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getDestination](#getDestination--) | Ruft ein Ziel ab, das angezeigt werden soll, wenn die Anmerkung aktiviert wird. |
| [getHighlighting](#getHighlighting--) | Ruft den visuellen Effekt ab, der verwendet werden soll, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt oder gehalten wird. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Legt eine Aktion fest, die ausgeführt werden soll, wenn die Link-Anmerkung aktiviert wird. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Legt ein Ziel fest, das angezeigt werden soll, wenn die Anmerkung aktiviert wird. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Legt den visuellen Effekt fest, der verwendet werden soll, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt oder gehalten wird. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstellt eine neue Link-Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Ruft eine Aktion ab, die ausgeführt werden soll, wenn die Link-Anmerkung aktiviert wird.

**Returns:**
PdfAction-Wert

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Ruft ein Ziel ab, das angezeigt werden soll, wenn die Anmerkung aktiviert wird.

**Returns:**
IAppointment‑Wert

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Ruft den visuellen Effekt ab, der verwendet werden soll, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt oder gehalten wird.

**Returns:**
HighlightingMode-Element @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Legt eine Aktion fest, die ausgeführt werden soll, wenn die Link-Anmerkung aktiviert wird.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Legt ein Ziel fest, das angezeigt werden soll, wenn die Anmerkung aktiviert wird.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Legt den visuellen Effekt fest, der verwendet werden soll, wenn die Maustaste innerhalb des aktiven Bereichs gedrückt oder gehalten wird.
