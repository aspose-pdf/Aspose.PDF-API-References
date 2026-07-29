---
title: "TableElement"
linktitle: "TableElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das Table-Strukturelement in der logischen Struktur dar."
type: docs
weight: 170
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Stellt das Table-Strukturelement in der logischen Struktur dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Konstruktor nur für den internen Gebrauch |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Position anpassen. |
| [createTBody](#createTBody--) | Erstellt {@link TableTHeadElement} und fügt es der aktuellen Tabelle hinzu. |
| [createTFoot](#createTFoot--) | Erstellt {@link TableTFootElement} und fügt es der aktuellen Tabelle hinzu. |
| [createTHead](#createTHead--) | Erstellt {@link TableTHeadElement} und fügt es der aktuellen Tabelle hinzu. |
| [getAlignment](#getAlignment--) | Liest oder setzt die Tabellenausrichtung. |
| [getBackgroundColor](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe der Tabelle. |
| [getBorder](#getBorder--) | Liest oder setzt den Tabellenrahmen. |
| [getBroken](#getBroken--) | Liest oder setzt die vertikale Unterbrechung der Tabelle; |
| [getColumnAdjustment](#getColumnAdjustment--) | Liest oder setzt die Spaltenanpassung der Tabelle. |
| [getColumnWidths](#getColumnWidths--) | Liefert die Spaltenbreiten der Tabelle. |
| [getCornerStyle](#getCornerStyle--) | Liest oder setzt die Stile der Rand-Ecken |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Liest den Standardzellenrahmen. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Liest oder setzt den Standardzellenabstand. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Liest oder setzt den Standard-Textzustand der Zelle. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Liest oder setzt die Standardspaltenbreite. |
| [getLeft](#getLeft--) | Liest oder setzt die linke Koordinate der Tabelle. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Liest oder setzt die maximale Spaltenanzahl für die Tabelle. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Liest die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Liest den Stil für wiederholende Zeilen. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Liest oder setzt die obere Koordinate der Tabelle. |
| [isBordersIncluded](#isBordersIncluded--) | Liest oder setzt den Rahmen, der in die Spaltenbreiten einbezogen ist. |
| [isBroken](#isBroken--) | Liest oder setzt, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Liest oder setzt die Tabellenausrichtung. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Liest oder setzt die Hintergrundfarbe der Tabelle. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Liest oder setzt den Tabellenrahmen. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Liest oder setzt den Rahmen, der in die Spaltenbreiten einbezogen ist. |
| [setBroken](#setBroken-boolean-) | Liest oder setzt, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten. |
| [setBroken](#setBroken-int-) | Liest oder setzt die vertikale Unterbrechung der Tabelle; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Liest oder setzt die Spaltenanpassung der Tabelle. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Liefert die Spaltenbreiten der Tabelle. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Liest oder setzt die Stile der Rand-Ecken |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Liest den Standardzellenrahmen. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Liest oder setzt den Standardzellenabstand. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Liest oder setzt den Standard-Textzustand der Zelle. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Liest oder setzt die Standardspaltenbreite. |
| [setLeft](#setLeft-float-) | Liest oder setzt die linke Koordinate der Tabelle. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Liest oder setzt die maximale Spaltenanzahl für die Tabelle. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Liest die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Liest den Stil für wiederholende Zeilen. |
| [setTop](#setTop-float-) | Liest oder setzt die obere Koordinate der Tabelle. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
Konstruktor nur für den internen Gebrauch

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Position anpassen.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Erstellt {@link TableTHeadElement} und fügt es der aktuellen Tabelle hinzu.

**Returns:**
Strukturelement erstellt.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Erstellt {@link TableTFootElement} und fügt es der aktuellen Tabelle hinzu.

**Returns:**
Strukturelement erstellt.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Erstellt {@link TableTHeadElement} und fügt es der aktuellen Tabelle hinzu.

**Returns:**
Strukturelement erstellt.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Liest oder setzt die Tabellenausrichtung.

**Returns:**
HorizontalAlignment-Element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Liest oder setzt die Hintergrundfarbe der Tabelle.

**Returns:**
Color-Instanz

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Liest oder setzt den Tabellenrahmen.

**Returns:**
BorderInfo‑Instanz

### getBroken {#getBroken--}
```
public final int getBroken()
```

Liest oder setzt die vertikale Unterbrechung der Tabelle;

**Returns:**
TableBroken-Element

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Liest oder setzt die Spaltenanpassung der Tabelle.

**Returns:**
ColumnAdjustment-Element

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Liefert die Spaltenbreiten der Tabelle.

**Returns:**
String Wert

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Liest oder setzt die Stile der Rand-Ecken

**Returns:**
BorderCornerStyle-Element

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

Liest oder setzt den Standardzellenabstand.

**Returns:**
MarginInfo‑Instanz

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Liest oder setzt den Standard-Textzustand der Zelle.

**Returns:**
TextState-Instanz

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Liest oder setzt die Standardspaltenbreite.

**Returns:**
String Wert

### getLeft {#getLeft--}
```
public final float getLeft()
```

Liest oder setzt die linke Koordinate der Tabelle.

**Returns:**
float-Wert

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Liest oder setzt die maximale Spaltenanzahl für die Tabelle.

**Returns:**
int-Wert

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Liest die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden.

**Returns:**
int-Wert

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Liest den Stil für wiederholende Zeilen.

**Returns:**
TextState-Instanz

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Liest oder setzt die obere Koordinate der Tabelle.

**Returns:**
float-Wert

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Liest oder setzt den Rahmen, der in die Spaltenbreiten einbezogen ist.

**Returns:**
boolescher Wert

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Liest oder setzt, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten.

**Returns:**
boolescher Wert

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Liest oder setzt die Tabellenausrichtung.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Liest oder setzt die Hintergrundfarbe der Tabelle.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Liest oder setzt den Tabellenrahmen.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Liest oder setzt den Rahmen, der in die Spaltenbreiten einbezogen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Liest oder setzt, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Liest oder setzt die vertikale Unterbrechung der Tabelle;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TableBroken-Element |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Liest oder setzt die Spaltenanpassung der Tabelle.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Liefert die Spaltenbreiten der Tabelle.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Liest oder setzt die Stile der Rand-Ecken

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Liest den Standardzellenrahmen.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Liest oder setzt den Standardzellenabstand.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Liest oder setzt den Standard-Textzustand der Zelle.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Liest oder setzt die Standardspaltenbreite.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Liest oder setzt die linke Koordinate der Tabelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Liest oder setzt die maximale Spaltenanzahl für die Tabelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Liest die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Liest den Stil für wiederholende Zeilen.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Liest oder setzt die obere Koordinate der Tabelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |
