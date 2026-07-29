---
title: "Cell"
linktitle: "Cell"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Zelle der Tabellenzeile dar."
type: docs
weight: 510
url: /de/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Stellt eine Zelle der Tabellenzeile dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Cell](#Cell--) | Initialisiert eine neue Instanz der Cell-Klasse. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz der Cell-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Kopiert die Zelle. |
| [getAlignment](#getAlignment--) | Liefert die Ausrichtung. |
| [getBackgroundColor](#getBackgroundColor--) | Liefert die Hintergrundfarbe. |
| [getBackgroundImage](#getBackgroundImage--) | Liefert oder setzt das Hintergrundbild |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Liefert die Hintergrundbilddatei. |
| [getBorder](#getBorder--) | Erhält den Rand. |
| [getColSpan](#getColSpan--) | Liefert oder setzt die Spaltenbreite. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Liefert den Standard-Zelltextzustand. |
| [getMargin](#getMargin--) | Liefert den Innenabstand. |
| [getParagraphs](#getParagraphs--) | Liefert den formatierten Text der Zelle. |
| [getRowSpan](#getRowSpan--) | Ermittelt die Zeilen­spanne. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt die vertikale Ausrichtung. |
| [getWidth](#getWidth--) | Ermittelt die Spaltenbreite. |
| [isNoBorder](#isNoBorder--) | Ermittelt, ob die Zelle einen Rahmen hat. |
| [isOverrideByFragment](#isOverrideByFragment--) | Legt fest, dass die TextState‑Eigenschaft der Zelle von der TextState‑Eigenschaft des TextFragments überschrieben wird. |
| [isWordWrapped](#isWordWrapped--) | Ermittelt, ob der Text der Zelle umgebrochen wird. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Legt die Ausrichtung fest. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Liest oder legt die Hintergrundfarbe fest. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Liefert oder setzt das Hintergrundbild |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Legt die Hintergrundbilddatei fest. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Setzt den Rand. |
| [setColSpan](#setColSpan-int-) | Legt die Spalten­spanne fest. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Setzt den Standard-Zelltextzustand. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Legt den Innenabstand fest. |
| [setNoBorder](#setNoBorder-boolean-) | Legt fest, dass die Zelle einen Rahmen hat. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Legt fest, dass die TextState‑Eigenschaft der Zelle von der TextState‑Eigenschaft des TextFragments überschrieben wird. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Legt den formatierten Text der Zelle fest. |
| [setRowSpan](#setRowSpan-int-) | Legt die Zeilen­spanne fest. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Legt die vertikale Ausrichtung fest. |
| [setWidth](#setWidth-double-) | Legt die Spaltenbreite fest. |
| [setWordWrapped](#setWordWrapped-boolean-) | Legt fest, ob der Text der Zelle umgebrochen wird. |

### Cell {#Cell--}
```
public Cell()
```

Initialisiert eine neue Instanz der Cell-Klasse.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz der Cell-Klasse.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Kopiert die Zelle.

**Returns:**
Das geklonte Objekt

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Liefert die Ausrichtung.

**Returns:**
HorizontalAlignment‑Element @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Liefert die Hintergrundfarbe.

**Returns:**
Color-Objekt

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Liefert oder setzt das Hintergrundbild

**Returns:**
Bildinstanz

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Liefert die Hintergrundbilddatei.

**Returns:**
String‑Wert @deprecated Eigenschaft wurde erweitert, bitte BackgroundImage verwenden

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Erhält den Rand.

**Returns:**
BorderInfo-Objekt

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Liefert oder setzt die Spaltenbreite.

**Returns:**
int-Wert

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Liefert den Standard-Zelltextzustand.

**Returns:**
TextState-Objekt

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Liefert den Innenabstand.

**Returns:**
MarginInfo‑Objekt

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Liefert den formatierten Text der Zelle.

**Returns:**
Paragraphs‑Objekt

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Ermittelt die Zeilen­spanne.

**Returns:**
int-Wert

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ermittelt die vertikale Ausrichtung.

**Returns:**
VerticalAlignment Element @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ermittelt die Spaltenbreite.

**Returns:**
double-Wert

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Ermittelt, ob die Zelle einen Rahmen hat.

**Returns:**
boolescher Wert

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Legt fest, dass die TextState‑Eigenschaft der Zelle von der TextState‑Eigenschaft des TextFragments überschrieben wird.

**Returns:**
boolescher Wert

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Ermittelt, ob der Text der Zelle umgebrochen wird.

**Returns:**
boolescher Wert

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Legt die Ausrichtung fest.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Liest oder legt die Hintergrundfarbe fest.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Liefert oder setzt das Hintergrundbild

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Legt die Hintergrundbilddatei fest.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Setzt den Rand.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Legt die Spalten­spanne fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Setzt den Standard-Zelltextzustand.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Legt den Innenabstand fest.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Legt fest, dass die Zelle einen Rahmen hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Legt fest, dass die TextState‑Eigenschaft der Zelle von der TextState‑Eigenschaft des TextFragments überschrieben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Legt den formatierten Text der Zelle fest.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Legt die Zeilen­spanne fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Legt die vertikale Ausrichtung fest.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Legt die Spaltenbreite fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Legt fest, ob der Text der Zelle umgebrochen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
