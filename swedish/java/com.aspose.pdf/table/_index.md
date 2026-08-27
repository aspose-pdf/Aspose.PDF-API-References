---
title: "Tabell"
linktitle: "Tabell"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en tabell som kan läggas till på sidan."
type: docs
weight: 4790
url: /sv/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Representerar en tabell som kan läggas till på sidan.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Table](#Table--) | Standardkonstruktor |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importerar endimensionell array av data till tabellen. Importen placerar en cell per varje array‑element och / * startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader / * fortfarande saknas (dvs. måltabellen är för liten för att absorbera all data), kommer nödvändiga rader att skapas / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Lägg till operatorer för rektangel. |
| [getAlignment](#getAlignment--) | Hämtar tabellens justering. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar tabellens bakgrundsfärg |
| [getBorder](#getBorder--) | Hämtar kanten. |
| [getBreakText](#getBreakText--) | Hämtar radbrytningstext för tabell |
| [getBroken](#getBroken--) | Hämtar eller anger vertikal brytning för tabell; |
| [getColumnAdjustment](#getColumnAdjustment--) | Hämtar tabellens kolumnjustering. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Hämta kolumnbredd |
| [getColumnWidths](#getColumnWidths--) | Hämtar kolumnbredderna för tabellen. |
| [getCornerStyle](#getCornerStyle--) | Hämtar stilarna för kantens hörn |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Hämtar standardcellram; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Hämtar standardcellens utfyllnad. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar standardcellens texttillstånd. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Hämtar standardcellram; |
| [getHeight](#getHeight--) | Hämta höjd. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Hämta höjd. |
| [getLeft](#getLeft--) | Hämtar tabellens vänstra koordinat. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Hämtar eller anger maximalt antal kolumner för tabell |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Hämtar antalet första rader som upprepas på flera sidor |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Hämtar stilen för upprepande rader |
| [getRows](#getRows--) | Hämtar raderna i tabellen. |
| [getTop](#getTop--) | Hämtar tabellens övre koordinat. |
| [getWidth](#getWidth--) | Hämta bredd. |
| [isBordersIncluded](#isBordersIncluded--) | Hämtar kant inkluderad i kolumnbredder. |
| [isBroken](#isBroken--) | Hämtar om tabellen är trasig - kommer att trunkeras för nästa sida. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Sätter tabelljusteringen. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sätter tabellens bakgrundsfärg |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Anger kanten. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Sätter kant inkluderad i kolumnbredder. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Sätter radbrytningstext för tabell |
| [setBroken](#setBroken-boolean-) | Sätter om tabellen är trasig - kommer att trunkeras för nästa sida. |
| [setBroken](#setBroken-int-) | Hämtar eller anger vertikal brytning för tabell; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Sätter tabellkolumnjusteringen. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Sätt höjd. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Hämtar kolumnbredderna för tabellen. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Hämtar eller sätter stilarna för kantens hörn |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Hämtar standardcellram; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sätter standardcellutfyllnad. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sätter standardcelltexttillstånd. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Hämtar standardcellram; |
| [setLeft](#setLeft-float-) | Ställer in tabellens vänstra koordinat. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Hämtar eller anger maximalt antal kolumner för tabell |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Hämtar antalet första rader som upprepas på flera sidor |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Hämtar stilen för upprepande rader |
| [setTop](#setTop-float-) | Ställer in tabellens övre koordinat. |

### Table {#Table--}
```
public Table()
```

Standardkonstruktor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importerar endimensionell array av data till tabellen. Importen placerar en cell per varje array‑element och / * startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader / * fortfarande saknas (dvs. måltabellen är för liten för att absorbera all data), kommer nödvändiga rader att skapas / * / *

**Returns:**
Det klonade objektet

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Lägg till operatorer för rektangel.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Hämtar tabellens justering.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hämtar tabellens bakgrundsfärg

**Returns:**
Color‑objekt

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Hämtar kanten.

**Returns:**
BorderInfo-objekt

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Hämtar radbrytningstext för tabell

**Returns:**
TextFragment objekt

### getBroken {#getBroken--}
```
public final int getBroken()
```

Hämtar eller anger vertikal brytning för tabell;

**Returns:**
TableBroken värde @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Hämtar tabellens kolumnjustering.

**Returns:**
ColumnAdjustment värde @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Hämta kolumnbredd

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Hämtar kolumnbredderna för tabellen.

**Returns:**
String värde

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Hämtar stilarna för kantens hörn

**Returns:**
BorderCornerStyle värde @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Hämtar standardcellram;

**Returns:**
BorderInfo-objekt

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Hämtar standardcellens utfyllnad.

**Returns:**
MarginInfo‑objekt

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Hämtar standardcellens texttillstånd.

**Returns:**
TextState värde

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Hämtar standardcellram;

**Returns:**
String-objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämta höjd.

**Returns:**
Tabellens höjd

### getHeight {#getHeight-com.aspose.pdf.Page-}
Hämta höjd.

**Returns:**
Tabellens höjd

### getLeft {#getLeft--}
```
public final float getLeft()
```

Hämtar tabellens vänstra koordinat.

**Returns:**
flyttalsvärde

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Hämtar eller anger maximalt antal kolumner för tabell

**Returns:**
int‑värde

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Hämtar antalet första rader som upprepas på flera sidor

**Returns:**
int‑värde

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Hämtar stilen för upprepande rader

**Returns:**
TextState-objekt

### getRows {#getRows--}
```
public final Rows getRows()
```

Hämtar raderna i tabellen.

**Returns:**
Rows-objekt

### getTop {#getTop--}
```
public final float getTop()
```

Hämtar tabellens övre koordinat.

**Returns:**
flyttalsvärde

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämta bredd.

**Returns:**
Tabellens bredd

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Hämtar kant inkluderad i kolumnbredder.

**Returns:**
booleskt värde

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Hämtar om tabellen är trasig - kommer att trunkeras för nästa sida.

**Returns:**
booleskt värde

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Sätter tabelljusteringen.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sätter tabellens bakgrundsfärg

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Anger kanten.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Sätter kant inkluderad i kolumnbredder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Sätter radbrytningstext för tabell

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Sätter om tabellen är trasig - kommer att trunkeras för nästa sida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Hämtar eller anger vertikal brytning för tabell;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TableBroken värde @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Sätter tabellkolumnjusteringen.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Sätt höjd.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Hämtar kolumnbredderna för tabellen.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Hämtar eller sätter stilarna för kantens hörn

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Hämtar standardcellram;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Sätter standardcellutfyllnad.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Sätter standardcelltexttillstånd.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Hämtar standardcellram;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Ställer in tabellens vänstra koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Hämtar eller anger maximalt antal kolumner för tabell

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Hämtar antalet första rader som upprepas på flera sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Hämtar stilen för upprepande rader

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Ställer in tabellens övre koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |
