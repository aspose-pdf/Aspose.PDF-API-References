---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Textfeld darstellt."
type: docs
weight: 4930
url: /de/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Klasse, die ein Textfeld darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc) |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Fügt Barcode 128 in das Feld ein. Der Feldwert wird in den Code geändert und das Feld wird schreibgeschützt. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Fügt ein Bild in die Feldressourcen ein und zeichnet es. |
| [getForceCombs](#getForceCombs--) | Liefert das Flag, das angibt, ob das Feld in getrennte Positionen unterteilt ist. |
| [getMaxLen](#getMaxLen--) | Liefert die maximale Textlänge im Feld. |
| [getMultiline](#getMultiline--) | Liefert das Mehrzeilen-Flag des Feldes. Wenn Mehrzeilen true ist, kann das Feld mehrere Textzeilen enthalten. |
| [getScrollable](#getScrollable--) | Liefert das scrollbare Flag des Feldes. Wenn true, kann das Feld gescrollt werden. |
| [getSpellCheck](#getSpellCheck--) | Liefert das Rechtschreibprüfungs-Flag für das Feld. Wenn true, wird das Feld rechtschreibgeprüft. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Liest oder setzt die vertikale Textausrichtung für die Anmerkung. |
| [getValue](#getValue--) | Liest den Wert des Feldes. |
| [setForceCombs](#setForceCombs-boolean-) | Setzt das Flag, das angibt, ob das Feld in getrennte Positionen unterteilt ist. |
| [setJustification](#setJustification-boolean-) | Setzt die Ausrichtung |
| [setMaxLen](#setMaxLen-int-) | Setzt die maximale Länge des Textes im Feld. |
| [setMultiline](#setMultiline-boolean-) | Setzt das Mehrzeilen-Flag des Feldes. Wenn Mehrzeilig true ist, kann das Feld mehrere Textzeilen enthalten. |
| [setScrollable](#setScrollable-boolean-) | Setzt das scrollbare Flag des Feldes. Wenn true, kann das Feld gescrollt werden. |
| [setSpellCheck](#setSpellCheck-boolean-) | Setzt das Rechtschreibprüfungs-Flag für das Feld. Wenn true, wird das Feld rechtschreibgeprüft. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Liest oder setzt die vertikale Textausrichtung für die Anmerkung. |
| [setValue](#setValue-java.lang.String-) | Setzt den Wert des Feldes. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Instanz von TextBoxField erstellen. @deprecated Für die volle Feldfunktionalität ist eine Bindung an das Dokument erforderlich - verwenden Sie TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Fügt Barcode 128 in das Feld ein. Der Feldwert wird in den Code geändert und das Feld wird schreibgeschützt.

### addImage {#addImage-java.awt.image.BufferedImage-}
Fügt ein Bild in die Feldressourcen ein und zeichnet es.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Liefert das Flag, das angibt, ob das Feld in getrennte Positionen unterteilt ist.

**Returns:**
boolescher Wert

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Liefert die maximale Textlänge im Feld.

**Returns:**
int-Wert

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Liefert das Mehrzeilen-Flag des Feldes. Wenn Mehrzeilen true ist, kann das Feld mehrere Textzeilen enthalten.

**Returns:**
boolescher Wert

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Liefert das scrollbare Flag des Feldes. Wenn true, kann das Feld gescrollt werden.

**Returns:**
boolescher Wert

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Liefert das Rechtschreibprüfungs-Flag für das Feld. Wenn true, wird das Feld rechtschreibgeprüft.

**Returns:**
boolescher Wert

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Liest oder setzt die vertikale Textausrichtung für die Anmerkung.

**Returns:**
VerticalAlignment-Element

### getValue {#getValue--}
```
public String getValue()
```

Liest den Wert des Feldes.

**Returns:**
String Wert

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Setzt das Flag, das angibt, ob das Feld in getrennte Positionen unterteilt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Setzt die Ausrichtung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Setzt die maximale Länge des Textes im Feld.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Setzt das Mehrzeilen-Flag des Feldes. Wenn Mehrzeilig true ist, kann das Feld mehrere Textzeilen enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Setzt das scrollbare Flag des Feldes. Wenn true, kann das Feld gescrollt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Setzt das Rechtschreibprüfungs-Flag für das Feld. Wenn true, wird das Feld rechtschreibgeprüft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Liest oder setzt die vertikale Textausrichtung für die Anmerkung.

### setValue {#setValue-java.lang.String-}
Setzt den Wert des Feldes.
