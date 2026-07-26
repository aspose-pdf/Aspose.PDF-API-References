---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Textanmerkung dar, die ein \\\"Haftnotiz\\\" ist, das an einem Punkt im PDF-Dokument befestigt ist."
type: docs
weight: 4920
url: /de/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Stellt eine Textannotation dar, die ein \"Haftnotiz\" ist und an einem Punkt im PDF-Dokument befestigt ist.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Erstelle TextAnnotation-Instanz |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Erstelle TextAnnotation-Instanz |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstelle TextAnnotation-Instanz |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Überschreibt die Definition in der Basisklasse mit einem leeren Körper. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getIcon](#getIcon--) | Liefert ein Symbol, das bei der Anzeige der Anmerkung verwendet wird. |
| [getOpen](#getOpen--) | Liefert ein Flag, das angibt, ob die Anmerkung zunächst geöffnet angezeigt werden soll. |
| [setIcon](#setIcon-int-) | Setzt ein Symbol, das bei der Anzeige der Anmerkung verwendet wird. |
| [setOpen](#setOpen-boolean-) | Setzt ein Flag, das angibt, ob die Anmerkung zunächst geöffnet angezeigt werden soll. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Erstelle TextAnnotation-Instanz

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Erstelle TextAnnotation-Instanz

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstelle TextAnnotation-Instanz

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Überschreibt die Definition in der Basisklasse mit einem leeren Körper.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Wert @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Liefert ein Symbol, das bei der Anzeige der Anmerkung verwendet wird.

**Returns:**
TextIcon-Wert @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Liefert ein Flag, das angibt, ob die Anmerkung zunächst geöffnet angezeigt werden soll.

**Returns:**
boolescher Wert

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Setzt ein Symbol, das bei der Anzeige der Anmerkung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TextIcon-Wert @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Setzt ein Flag, das angibt, ob die Anmerkung zunächst geöffnet angezeigt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
