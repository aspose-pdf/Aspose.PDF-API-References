---
title: "Tabelle"
linktitle: "Tabelle"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann."
type: docs
weight: 4790
url: /de/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Stellt eine Tabelle dar, die zur Seite hinzugefügt werden kann.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Table](#Table--) | Standardkonstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importiert ein eindimensionales Array von Daten in die Tabelle. Der Import legt für jedes Element des Arrays eine Zelle an und / * beginnt bei der in den Parametern definierten Zeile und Spalte. Während des Imports, wenn festgestellt wird, dass notwendige Zeilen / * noch fehlen (d.h. die Zieltabelle zu klein ist, um alle Daten aufzunehmen), werden die notwendigen Zeilen erstellt / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Operatoren für Rechteck hinzufügen. |
| [getAlignment](#getAlignment--) | Liefert die Tabellenausrichtung. |
| [getBackgroundColor](#getBackgroundColor--) | Liefert die Tabellenhintergrundfarbe |
| [getBorder](#getBorder--) | Erhält den Rand. |
| [getBreakText](#getBreakText--) | Liefert den Umbruchtext für die Tabelle |
| [getBroken](#getBroken--) | Liefert oder setzt die vertikale Unterbrechung der Tabelle; |
| [getColumnAdjustment](#getColumnAdjustment--) | Liefert die Spaltenanpassung der Tabelle. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Spaltenbreite ermitteln |
| [getColumnWidths](#getColumnWidths--) | Liefert die Spaltenbreiten der Tabelle. |
| [getCornerStyle](#getCornerStyle--) | Liefert die Stile der Rand-Ecken |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Liefert den Standardzellenrand; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Liefert das Standard-Zellenpadding. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Liefert den Standard-Zelltextzustand. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Liefert den Standardzellenrand; |
| [getHeight](#getHeight--) | Höhe ermitteln. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Höhe ermitteln. |
| [getLeft](#getLeft--) | Ermittelt die linke Koordinate der Tabelle. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Liefert oder setzt die maximale Spaltenanzahl für die Tabelle |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Liefert die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Ruft den Stil für wiederholende Zeilen ab |
| [getRows](#getRows--) | Ruft die Zeilen der Tabelle ab. |
| [getTop](#getTop--) | Erhält die obere Tabellenkoordinate. |
| [getWidth](#getWidth--) | Ruft die Breite ab. |
| [isBordersIncluded](#isBordersIncluded--) | Ruft den Rand, der in Spaltenbreiten einbezogen ist, ab. |
| [isBroken](#isBroken--) | Ruft ab, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Setzt die Tabellenausrichtung. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Setzt die Tabellenhintergrundfarbe |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Setzt den Rand. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Setzt den Rand, der in Spaltenbreiten einbezogen ist. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Setzt den Umbruchtext für die Tabelle |
| [setBroken](#setBroken-boolean-) | Setzt, dass die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten. |
| [setBroken](#setBroken-int-) | Liefert oder setzt die vertikale Unterbrechung der Tabelle; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Setzt die Tabellenspaltenanpassung. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Setzt die Höhe. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Liefert die Spaltenbreiten der Tabelle. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Liest oder setzt die Stile der Rand-Ecken |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Liefert den Standardzellenrand; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Setzt das Standard-Zellenpadding. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Setzt den Standard-Zelltextzustand. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Liefert den Standardzellenrand; |
| [setLeft](#setLeft-float-) | Legt die linke Koordinate der Tabelle fest. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Liefert oder setzt die maximale Spaltenanzahl für die Tabelle |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Liefert die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Ruft den Stil für wiederholende Zeilen ab |
| [setTop](#setTop-float-) | Setzt die obere Tabellenkoordinate. |

### Table {#Table--}
```
public Table()
```

Standardkonstruktor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importiert ein eindimensionales Array von Daten in die Tabelle. Der Import legt für jedes Element des Arrays eine Zelle an und / * beginnt bei der in den Parametern definierten Zeile und Spalte. Während des Imports, wenn festgestellt wird, dass notwendige Zeilen / * noch fehlen (d.h. die Zieltabelle zu klein ist, um alle Daten aufzunehmen), werden die notwendigen Zeilen erstellt / * / *

**Returns:**
Das geklonte Objekt

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Operatoren für Rechteck hinzufügen.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Liefert die Tabellenausrichtung.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Liefert die Tabellenhintergrundfarbe

**Returns:**
Color-Objekt

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Erhält den Rand.

**Returns:**
BorderInfo-Objekt

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Liefert den Umbruchtext für die Tabelle

**Returns:**
TextFragment-Objekt

### getBroken {#getBroken--}
```
public final int getBroken()
```

Liefert oder setzt die vertikale Unterbrechung der Tabelle;

**Returns:**
TableBroken-Wert @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Liefert die Spaltenanpassung der Tabelle.

**Returns:**
ColumnAdjustment-Wert @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Spaltenbreite ermitteln

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

Liefert die Stile der Rand-Ecken

**Returns:**
BorderCornerStyle-Wert @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Liefert den Standardzellenrand;

**Returns:**
BorderInfo-Objekt

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Liefert das Standard-Zellenpadding.

**Returns:**
MarginInfo‑Objekt

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Liefert den Standard-Zelltextzustand.

**Returns:**
TextState-Wert

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Liefert den Standardzellenrand;

**Returns:**
String-Objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Höhe ermitteln.

**Returns:**
Die Tabellenhöhe

### getHeight {#getHeight-com.aspose.pdf.Page-}
Höhe ermitteln.

**Returns:**
Die Tabellenhöhe

### getLeft {#getLeft--}
```
public final float getLeft()
```

Ermittelt die linke Koordinate der Tabelle.

**Returns:**
float-Wert

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Liefert oder setzt die maximale Spaltenanzahl für die Tabelle

**Returns:**
int-Wert

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Liefert die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden

**Returns:**
int-Wert

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Ruft den Stil für wiederholende Zeilen ab

**Returns:**
TextState-Objekt

### getRows {#getRows--}
```
public final Rows getRows()
```

Ruft die Zeilen der Tabelle ab.

**Returns:**
Rows-Objekt

### getTop {#getTop--}
```
public final float getTop()
```

Erhält die obere Tabellenkoordinate.

**Returns:**
float-Wert

### getWidth {#getWidth--}
```
public double getWidth()
```

Ruft die Breite ab.

**Returns:**
Die Tabellenbreite

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Ruft den Rand, der in Spaltenbreiten einbezogen ist, ab.

**Returns:**
boolescher Wert

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Ruft ab, ob die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten.

**Returns:**
boolescher Wert

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Setzt die Tabellenausrichtung.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Setzt die Tabellenhintergrundfarbe

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Setzt den Rand.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Setzt den Rand, der in Spaltenbreiten einbezogen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Setzt den Umbruchtext für die Tabelle

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Setzt, dass die Tabelle unterbrochen ist – wird für die nächste Seite abgeschnitten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Liefert oder setzt die vertikale Unterbrechung der Tabelle;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TableBroken-Wert @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Setzt die Tabellenspaltenanpassung.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Setzt die Höhe.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Liefert die Spaltenbreiten der Tabelle.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Liest oder setzt die Stile der Rand-Ecken

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Liefert den Standardzellenrand;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Setzt das Standard-Zellenpadding.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Setzt den Standard-Zelltextzustand.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Liefert den Standardzellenrand;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Legt die linke Koordinate der Tabelle fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Liefert oder setzt die maximale Spaltenanzahl für die Tabelle

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Liefert die Anzahl der ersten Zeilen, die für mehrere Seiten wiederholt werden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Ruft den Stil für wiederholende Zeilen ab

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Setzt die obere Tabellenkoordinate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |
