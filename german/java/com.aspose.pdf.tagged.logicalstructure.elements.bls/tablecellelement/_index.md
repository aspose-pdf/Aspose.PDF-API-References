---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Basisklasse für Tabellenzellen-Elemente (TH und TD) in der logischen Struktur dar."
type: docs
weight: 150
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Stellt eine Basisklasse für Tabellenzellen-Elemente (TH und TD) in der logischen Struktur dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Position anpassen. |
| [getAlignment](#getAlignment--) | Liest oder setzt die Zellausrichtung. |
| [getBackgroundColor](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe der Zelle. |
| [getBorder](#getBorder--) | Liest oder setzt den Zellenrand. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Liefert oder setzt die Spaltenbreite. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Liest oder setzt den Standard-Textzustand der Zelle. |
| [getMargin](#getMargin--) | Liest oder setzt den Innenabstand. |
| [getRowSpan](#getRowSpan--) | Liest oder setzt die Zeilenüberlappung. |
| [getStructureTextState](#getStructureTextState--) | Liest {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. Wert: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt oder legt die vertikale Ausrichtung fest. |
| [isNoBorder](#isNoBorder--) | Liest oder setzt, ob die Zelle einen Rand hat. |
| [isWordWrapped](#isWordWrapped--) | Liest oder setzt, ob der Zellentext umbrochen wird. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Liest oder setzt die Zellausrichtung. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Liest oder setzt die Hintergrundfarbe der Zelle. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Liest oder setzt den Zellenrand. |
| [setColSpan](#setColSpan-int-) | Liefert oder setzt die Spaltenbreite. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Liest oder setzt den Standard-Textzustand der Zelle. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Liest oder setzt den Innenabstand. |
| [setNoBorder](#setNoBorder-boolean-) | Liest oder setzt, ob die Zelle einen Rand hat. |
| [setRowSpan](#setRowSpan-int-) | Liest oder setzt die Zeilenüberlappung. |
| [setText](#setText-java.lang.String-) | Fügt Textinhalt zum aktuellen Textelement hinzu. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ermittelt oder legt die vertikale Ausrichtung fest. |
| [setWordWrapped](#setWordWrapped-boolean-) | Liest oder setzt, ob der Zellentext umbrochen wird. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Position anpassen.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Liest oder setzt die Zellausrichtung.

**Returns:**
HorizontalAlignment-Element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Liest oder setzt die Hintergrundfarbe der Zelle.

**Returns:**
Color-Instanz

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Liest oder setzt den Zellenrand.

**Returns:**
BorderInfo‑Instanz

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Liefert oder setzt die Spaltenbreite.

**Returns:**
int-Wert

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Liest oder setzt den Standard-Textzustand der Zelle.

**Returns:**
TextState-Instanz

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Liest oder setzt den Innenabstand.

**Returns:**
MarginInfo‑Instanz

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Liest oder setzt die Zeilenüberlappung.

**Returns:**
int-Wert

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Liest {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element. Wert: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} Objekt für das aktuelle Element.

**Returns:**
StructureTextState instance

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Ermittelt oder legt die vertikale Ausrichtung fest.

**Returns:**
VerticalAlignment-Element

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Liest oder setzt, ob die Zelle einen Rand hat.

**Returns:**
boolescher Wert

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Liest oder setzt, ob der Zellentext umbrochen wird.

**Returns:**
boolescher Wert

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Liest oder setzt die Zellausrichtung.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Liest oder setzt die Hintergrundfarbe der Zelle.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Liest oder setzt den Zellenrand.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Liefert oder setzt die Spaltenbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Liest oder setzt den Standard-Textzustand der Zelle.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Liest oder setzt den Innenabstand.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Liest oder setzt, ob die Zelle einen Rand hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Liest oder setzt die Zeilenüberlappung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setText {#setText-java.lang.String-}
Fügt Textinhalt zum aktuellen Textelement hinzu.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ermittelt oder legt die vertikale Ausrichtung fest.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Liest oder setzt, ob der Zellentext umbrochen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
