---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Abstrakte Klasse, die eine Markup-Annotation darstellt."
type: docs
weight: 2870
url: /de/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Abstrakte Klasse, die eine Markup-Annotation darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Konstruktor |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clearState](#clearState--) | Löscht den Zustand und das Zustandsmodell für die Anmerkung. Beispielsweise wird der Überprüfungsstatus einer Anmerkung gelöscht. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [getCreationDate](#getCreationDate--) | Gibt Datum und Uhrzeit zurück, wann die Anmerkung erstellt wurde. |
| [getInReplyTo](#getInReplyTo--) | Ein Verweis auf die Anmerkung, auf die diese Anmerkung "in Antwort auf" ist. Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| [getOpacity](#getOpacity--) | Gibt den konstanten Deckkraftwert zurück, der beim Rendern der Anmerkung verwendet wird. |
| [getPopup](#getPopup--) | Popup‑Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes. |
| [getReplyType](#getReplyType--) | Eine Zeichenkette, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung spezifiziert. |
| [getRichText](#getRichText--) | Gibt eine Rich‑Text‑Zeichenkette zurück, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Gibt eine Rich‑Text‑Zeichenkette zurück, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird. |
| [getState](#getState--) | Gibt den Zustand der Anmerkung zurück. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [getStateModel](#getStateModel--) | Gibt das Zustandsmodell der Anmerkung zurück. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [getSubject](#getSubject--) | Gibt den Text zurück, der die Beschreibung des Objekts darstellt. |
| [getTitle](#getTitle--) | Gibt ein Textlabel zurück, das in der Titelleiste des Popup‑Fensters der Anmerkung angezeigt wird, wenn es geöffnet und aktiv ist. Dieser Eintrag soll den Benutzer identifizieren, der die Anmerkung hinzugefügt hat. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Gibt Datum und Uhrzeit zurück, wann die Anmerkung erstellt wurde. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Ein Verweis auf die Anmerkung, auf die diese Anmerkung "in Antwort auf" ist. Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| [setMarkedState](#setMarkedState-boolean-) | Setzt den markierten und unmarkierten Zustand für die Anmerkung. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [setOpacity](#setOpacity-double-) | Setzt den konstanten Deckkraftwert, der beim Rendern der Anmerkung verwendet wird. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Popup‑Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Eine Zeichenkette, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung spezifiziert. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Review‑StateModel gehören. Der Zustand wird von dem Benutzer gesetzt, der die Zielanmerkung erstellt hat. Der Wert wird aus der Title‑Eigenschaft der Zielanmerkung übernommen. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Review‑StateModel gehören. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen. |
| [setRichText](#setRichText-java.lang.String-) | Setzt eine Rich‑Text‑Zeichenkette, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird. |
| [setSubject](#setSubject-java.lang.String-) | Setzt den Text, der die Beschreibung des Objekts darstellt. |
| [setTitle](#setTitle-java.lang.String-) | Setzt ein Textlabel, das in der Titelleiste des Popup‑Fensters der Anmerkung angezeigt wird, wenn es geöffnet und aktiv ist. Dieser Eintrag soll den Benutzer identifizieren, der die Anmerkung hinzugefügt hat. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Konstruktor

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Konstruktor

### clearState {#clearState--}
```
public final void clearState()
```

Löscht den Zustand und das Zustandsmodell für die Anmerkung. Beispielsweise wird der Überprüfungsstatus einer Anmerkung gelöscht. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Gibt Datum und Uhrzeit zurück, wann die Anmerkung erstellt wurde.

**Returns:**
Date-Objekt

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Ein Verweis auf die Anmerkung, auf die diese Anmerkung "in Antwort auf" ist. Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden.

**Returns:**
Anmerkungswert

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Gibt den konstanten Deckkraftwert zurück, der beim Rendern der Anmerkung verwendet wird.

**Returns:**
double-Wert

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Popup‑Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes.

**Returns:**
PopupAnnotation‑Wert

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Eine Zeichenkette, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung spezifiziert.

**Returns:**
ReplyType‑Wert @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Gibt eine Rich‑Text‑Zeichenkette zurück, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird.

**Returns:**
String Wert

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Gibt eine Rich‑Text‑Zeichenkette zurück, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird.

**Returns:**
String Wert

### getState {#getState--}
```
public final AnnotationState getState()
```

Gibt den Zustand der Anmerkung zurück. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

**Returns:**
Anmerkungszustand.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Gibt das Zustandsmodell der Anmerkung zurück. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

**Returns:**
Anmerkungszustandsmodell.

### getSubject {#getSubject--}
```
public String getSubject()
```

Gibt den Text zurück, der die Beschreibung des Objekts darstellt.

**Returns:**
String Wert

### getTitle {#getTitle--}
```
public String getTitle()
```

Gibt ein Textlabel zurück, das in der Titelleiste des Popup‑Fensters der Anmerkung angezeigt wird, wenn es geöffnet und aktiv ist. Dieser Eintrag soll den Benutzer identifizieren, der die Anmerkung hinzugefügt hat.

**Returns:**
String Wert

### setCreationDate {#setCreationDate-java.util.Date-}
Gibt Datum und Uhrzeit zurück, wann die Anmerkung erstellt wurde.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Ein Verweis auf die Anmerkung, auf die diese Anmerkung "in Antwort auf" ist. Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Setzt den markierten und unmarkierten Zustand für die Anmerkung. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| markiert |  | Wahr, wenn der Markiert‑Zustand gesetzt wird, und falsch, wenn der Unmarkiert‑Zustand gesetzt wird. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Setzt den konstanten Deckkraftwert, der beim Rendern der Anmerkung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Popup‑Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Eine Zeichenkette, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung und einer durch InReplyTo angegebenen Anmerkung spezifiziert.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Review‑StateModel gehören. Der Zustand wird von dem Benutzer gesetzt, der die Zielanmerkung erstellt hat. Der Wert wird aus der Title‑Eigenschaft der Zielanmerkung übernommen. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Setzt den Überprüfungszustand für eine Anmerkung. Markierte und unmarkierte Zustände werden ignoriert, da sie nicht zum Review‑StateModel gehören. Hinweis: Der Zustand wird in anderen Textanmerkungen gespeichert, die Schlüssel für Zustand und Zustandsmodell besitzen.

### setRichText {#setRichText-java.lang.String-}
Setzt eine Rich‑Text‑Zeichenkette, die im Popup‑Fenster angezeigt wird, wenn die Anmerkung geöffnet wird.

### setSubject {#setSubject-java.lang.String-}
Setzt den Text, der die Beschreibung des Objekts darstellt.

### setTitle {#setTitle-java.lang.String-}
Setzt ein Textlabel, das in der Titelleiste des Popup‑Fensters der Anmerkung angezeigt wird, wenn es geöffnet und aktiv ist. Dieser Eintrag soll den Benutzer identifizieren, der die Anmerkung hinzugefügt hat.
