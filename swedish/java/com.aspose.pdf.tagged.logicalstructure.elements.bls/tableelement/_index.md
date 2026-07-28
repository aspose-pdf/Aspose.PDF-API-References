---
title: "TableElement"
linktitle: "TableElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar Table-strukturelement i logisk struktur."
type: docs
weight: 170
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Representerar Table-strukturelement i logisk struktur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | konstruktör endast för internt bruk |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Justera position. |
| [createTBody](#createTBody--) | Skapar {@link TableTHeadElement} och lägger till den i den aktuella tabellen. |
| [createTFoot](#createTFoot--) | Skapar {@link TableTFootElement} och lägger till den i den aktuella tabellen. |
| [createTHead](#createTHead--) | Skapar {@link TableTHeadElement} och lägger till den i den aktuella tabellen. |
| [getAlignment](#getAlignment--) | Hämtar eller anger tabellens justering. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar eller anger tabellens bakgrundsfärg. |
| [getBorder](#getBorder--) | Hämtar eller anger tabellens kant. |
| [getBroken](#getBroken--) | Hämtar eller anger tabellens vertikala brytning; |
| [getColumnAdjustment](#getColumnAdjustment--) | Hämtar eller anger tabellens kolumnjustering. |
| [getColumnWidths](#getColumnWidths--) | Hämtar kolumnbredderna för tabellen. |
| [getCornerStyle](#getCornerStyle--) | Hämtar eller sätter stilarna för kantens hörn |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Hämtar standardcellkant. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Hämtar eller anger standardcellpadding. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar eller anger standardcellens texttillstånd. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Hämtar eller anger standardkolumnbredd. |
| [getLeft](#getLeft--) | Hämtar eller anger tabellens vänstra koordinat. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Hämtar eller anger maximalt antal kolumner för tabellen. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Hämtar antalet första rader som upprepas på flera sidor. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Hämtar stilen för upprepande rader. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Hämtar eller anger tabellens övre koordinat. |
| [isBordersIncluded](#isBordersIncluded--) | Hämtar eller anger kant inkluderad i kolumnwidhts. |
| [isBroken](#isBroken--) | Hämtar eller anger om tabellen är bruten – kommer att trunkeras för nästa sida. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Hämtar eller anger tabellens justering. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hämtar eller anger tabellens bakgrundsfärg. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Hämtar eller anger tabellens kant. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Hämtar eller anger kant inkluderad i kolumnwidhts. |
| [setBroken](#setBroken-boolean-) | Hämtar eller anger om tabellen är bruten – kommer att trunkeras för nästa sida. |
| [setBroken](#setBroken-int-) | Hämtar eller anger tabellens vertikala brytning; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Hämtar eller anger tabellens kolumnjustering. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Hämtar kolumnbredderna för tabellen. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Hämtar eller sätter stilarna för kantens hörn |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Hämtar standardcellkant. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Hämtar eller anger standardcellpadding. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Hämtar eller anger standardcellens texttillstånd. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Hämtar eller anger standardkolumnbredd. |
| [setLeft](#setLeft-float-) | Hämtar eller anger tabellens vänstra koordinat. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Hämtar eller anger maximalt antal kolumner för tabellen. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Hämtar antalet första rader som upprepas på flera sidor. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Hämtar stilen för upprepande rader. |
| [setTop](#setTop-float-) | Hämtar eller anger tabellens övre koordinat. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
konstruktör endast för internt bruk

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Justera position.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Skapar {@link TableTHeadElement} och lägger till den i den aktuella tabellen.

**Returns:**
Skapat strukturelement.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Skapar {@link TableTFootElement} och lägger till den i den aktuella tabellen.

**Returns:**
Skapat strukturelement.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Skapar {@link TableTHeadElement} och lägger till den i den aktuella tabellen.

**Returns:**
Skapat strukturelement.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Hämtar eller anger tabellens justering.

**Returns:**
HorizontalAlignment-element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hämtar eller anger tabellens bakgrundsfärg.

**Returns:**
Color-instans

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Hämtar eller anger tabellens kant.

**Returns:**
BorderInfo instans

### getBroken {#getBroken--}
```
public final int getBroken()
```

Hämtar eller anger tabellens vertikala brytning;

**Returns:**
TableBroken element

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Hämtar eller anger tabellens kolumnjustering.

**Returns:**
ColumnAdjustment element

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

Hämtar eller sätter stilarna för kantens hörn

**Returns:**
BorderCornerStyle element

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Hämtar standardcellkant.

**Returns:**
BorderInfo instans

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Hämtar eller anger standardcellpadding.

**Returns:**
MarginInfo instans

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Hämtar eller anger standardcellens texttillstånd.

**Returns:**
TextState-instans

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Hämtar eller anger standardkolumnbredd.

**Returns:**
String värde

### getLeft {#getLeft--}
```
public final float getLeft()
```

Hämtar eller anger tabellens vänstra koordinat.

**Returns:**
flyttalsvärde

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Hämtar eller anger maximalt antal kolumner för tabellen.

**Returns:**
int‑värde

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Hämtar antalet första rader som upprepas på flera sidor.

**Returns:**
int‑värde

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Hämtar stilen för upprepande rader.

**Returns:**
TextState-instans

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Hämtar eller anger tabellens övre koordinat.

**Returns:**
flyttalsvärde

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Hämtar eller anger kant inkluderad i kolumnwidhts.

**Returns:**
booleskt värde

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Hämtar eller anger om tabellen är bruten – kommer att trunkeras för nästa sida.

**Returns:**
booleskt värde

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Hämtar eller anger tabellens justering.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hämtar eller anger tabellens bakgrundsfärg.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Hämtar eller anger tabellens kant.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Hämtar eller anger kant inkluderad i kolumnwidhts.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Hämtar eller anger om tabellen är bruten – kommer att trunkeras för nästa sida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Hämtar eller anger tabellens vertikala brytning;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TableBroken element |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Hämtar eller anger tabellens kolumnjustering.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Hämtar kolumnbredderna för tabellen.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Hämtar eller sätter stilarna för kantens hörn

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Hämtar standardcellkant.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Hämtar eller anger standardcellpadding.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Hämtar eller anger standardcellens texttillstånd.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Hämtar eller anger standardkolumnbredd.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Hämtar eller anger tabellens vänstra koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Hämtar eller anger maximalt antal kolumner för tabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Hämtar antalet första rader som upprepas på flera sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Hämtar stilen för upprepande rader.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Hämtar eller anger tabellens övre koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |
