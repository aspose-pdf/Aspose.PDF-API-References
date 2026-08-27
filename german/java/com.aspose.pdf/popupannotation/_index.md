---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Pop‑Up‑Annotation dar, die Text in einem Pop‑Up‑Fenster zur Eingabe und Bearbeitung anzeigt."
type: docs
weight: 3930
url: /de/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Stellt die Pop‑Up‑Annotation dar, die Text in einem Pop‑Up‑Fenster zur Eingabe und Bearbeitung anzeigt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Konstruktor. zur Verwendung im Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstellt eine neue Popup-Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getOpen](#getOpen--) | Liefert ein Flag, das angibt, ob die Pop-up-Anmerkung zunächst geöffnet angezeigt werden soll. |
| [getParent](#getParent--) | Liefert die übergeordnete Anmerkung, mit der diese Pop-up-Anmerkung verknüpft sein soll. Wenn dieser Eintrag vorhanden ist, überschreiben die Contents, M, C und T Einträge der übergeordneten Anmerkung jene der Pop-up-Anmerkung selbst. |
| [setOpen](#setOpen-boolean-) | Setzt ein Flag, das angibt, ob die Pop-up-Anmerkung zunächst geöffnet angezeigt werden soll. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Legt die übergeordnete Anmerkung fest, mit der diese Pop-up-Anmerkung verknüpft werden soll. Wenn dieser Eintrag vorhanden ist, überschreiben die Inhalte, M-, C- und T-Einträge der übergeordneten Anmerkung die der Pop-up-Anmerkung selbst. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Konstruktor. zur Verwendung im Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstellt eine neue Popup-Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Liefert ein Flag, das angibt, ob die Pop-up-Anmerkung zunächst geöffnet angezeigt werden soll.

**Returns:**
boolescher Wert

### getParent {#getParent--}
```
public Annotation getParent()
```

Liefert die übergeordnete Anmerkung, mit der diese Pop-up-Anmerkung verknüpft sein soll. Wenn dieser Eintrag vorhanden ist, überschreiben die Contents, M, C und T Einträge der übergeordneten Anmerkung jene der Pop-up-Anmerkung selbst.

**Returns:**
MarkupAnnotation-Objekt

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Setzt ein Flag, das angibt, ob die Pop-up-Anmerkung zunächst geöffnet angezeigt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Legt die übergeordnete Anmerkung fest, mit der diese Pop-up-Anmerkung verknüpft werden soll. Wenn dieser Eintrag vorhanden ist, überschreiben die Inhalte, M-, C- und T-Einträge der übergeordneten Anmerkung die der Pop-up-Anmerkung selbst.
