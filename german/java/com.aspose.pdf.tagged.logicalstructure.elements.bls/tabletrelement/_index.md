---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das TR-Strukturelement in der logischen Struktur der Tabelle dar."
type: docs
weight: 240
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Stellt das TR-Strukturelement in der logischen Struktur der Tabelle dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Konstruktor nur für den internen Gebrauch |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createTD](#createTD--) | Erstellt {@link TableTHElement} und fügt es der aktuellen Tabelle hinzu. |
| [createTH](#createTH--) | Erstellt {@link TableTHElement} und fügt es der aktuellen Tabelle hinzu. |
| [getBackgroundColor](#getBackgroundColor--) | Liest oder setzt die Zeilenhintergrundfarbe. |
| [getBorder](#getBorder--) | Liest oder setzt den Zeilenrand. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Liest den Standardzellenrahmen. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Liest oder setzt den Standardabstand für Zeilenzellen. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Liest oder setzt den Standard‑Textzustand für Zeilenzellen. |
| [getFixedRowHeight](#getFixedRowHeight--) | Liest die feste Zeilenhöhe – die Zeile kann eine feste Höhe haben. |
| [getMinRowHeight](#getMinRowHeight--) | Liest die Höhe der Zeile. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt oder legt die vertikale Ausrichtung fest. |
| [isInNewPage](#isInNewPage--) | Liest, ob die feste Zeile auf einer neuen Seite ist – Seite mit dieser Eigenschaft sollte auf die nächste Seite gedruckt werden. Standard: false. |
| [isRowBroken](#isRowBroken--) | Liest, ob die Zeile zwischen zwei Seiten umgebrochen werden kann. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Liest oder setzt die Zeilenhintergrundfarbe. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Liest oder setzt den Zeilenrand. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Liest den Standardzellenrahmen. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Liest oder setzt den Standardabstand für Zeilenzellen. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Liest oder setzt den Standard‑Textzustand für Zeilenzellen. |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Liest die feste Zeilenhöhe – die Zeile kann eine feste Höhe haben. |
| [setInNewPage](#setInNewPage-boolean-) | Liest, ob die feste Zeile auf einer neuen Seite ist – Seite mit dieser Eigenschaft sollte auf die nächste Seite gedruckt werden. Standard: false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Liest die Höhe der Zeile. |
| [setRowBroken](#setRowBroken-boolean-) | Liest, ob die Zeile zwischen zwei Seiten umgebrochen werden kann. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ermittelt oder legt die vertikale Ausrichtung fest. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
Konstruktor nur für den internen Gebrauch

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Erstellt {@link TableTHElement} und fügt es der aktuellen Tabelle hinzu.

**Returns:**
Strukturelement erstellt.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Erstellt {@link TableTHElement} und fügt es der aktuellen Tabelle hinzu.

**Returns:**
Strukturelement erstellt.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Liest oder setzt die Zeilenhintergrundfarbe.

**Returns:**
Color-Instanz

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Liest oder setzt den Zeilenrand.

**Returns:**
BorderInfo‑Instanz

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Liest den Standardzellenrahmen.

**Returns:**
BorderInfo‑Instanz

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Liest oder setzt den Standardabstand für Zeilenzellen.

**Returns:**
MarginInfo‑Instanz

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Liest oder setzt den Standard‑Textzustand für Zeilenzellen.

**Returns:**
TextState-Instanz

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Liest die feste Zeilenhöhe – die Zeile kann eine feste Höhe haben.

**Returns:**
double-Wert

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Liest die Höhe der Zeile.

**Returns:**
double-Wert

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Ermittelt oder legt die vertikale Ausrichtung fest.

**Returns:**
VerticalAlignment-Element

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Liest, ob die feste Zeile auf einer neuen Seite ist – Seite mit dieser Eigenschaft sollte auf die nächste Seite gedruckt werden. Standard: false.

**Returns:**
boolescher Wert

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Liest, ob die Zeile zwischen zwei Seiten umgebrochen werden kann.

**Returns:**
boolescher Wert

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Liest oder setzt die Zeilenhintergrundfarbe.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Liest oder setzt den Zeilenrand.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Liest den Standardzellenrahmen.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Liest oder setzt den Standardabstand für Zeilenzellen.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Liest oder setzt den Standard‑Textzustand für Zeilenzellen.

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Liest die feste Zeilenhöhe – die Zeile kann eine feste Höhe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Liest, ob die feste Zeile auf einer neuen Seite ist – Seite mit dieser Eigenschaft sollte auf die nächste Seite gedruckt werden. Standard: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Liest die Höhe der Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Liest, ob die Zeile zwischen zwei Seiten umgebrochen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ermittelt oder legt die vertikale Ausrichtung fest.
