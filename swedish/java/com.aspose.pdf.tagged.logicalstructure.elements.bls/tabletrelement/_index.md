---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar TR-strukturelement i den logiska strukturen för tabellen."
type: docs
weight: 240
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Representerar TR-strukturelement i den logiska strukturen för tabellen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | konstruktör endast för internt bruk |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createTD](#createTD--) | Skapar {@link TableTHElement} och lägger till den i den aktuella tabellen. |
| [createTH](#createTH--) | Skapar {@link TableTHElement} och lägger till den i den aktuella tabellen. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar eller anger radens bakgrundsfärg. |
| [getBorder](#getBorder--) | Hämtar eller anger radens kant. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Hämtar standardcellkant. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Hämtar eller anger standardmarginal för radceller. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar eller anger standardtexttillstånd för radceller. |
| [getFixedRowHeight](#getFixedRowHeight--) | Hämtar fast radhöjd – raden kan ha fast höjd. |
| [getMinRowHeight](#getMinRowHeight--) | Hämtar höjd för raden. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar eller anger vertikal justering. |
| [isInNewPage](#isInNewPage--) | Hämtar om fast rad är på en ny sida – sidan med denna egenskap bör skrivas ut på nästa sida. Standard falskt. |
| [isRowBroken](#isRowBroken--) | Hämtar om raden kan brytas mellan två sidor. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Hämtar eller anger radens bakgrundsfärg. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Hämtar eller anger radens kant. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Hämtar standardcellkant. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Hämtar eller anger standardmarginal för radceller. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Hämtar eller anger standardtexttillstånd för radceller. |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Hämtar fast radhöjd – raden kan ha fast höjd. |
| [setInNewPage](#setInNewPage-boolean-) | Hämtar om fast rad är på en ny sida – sidan med denna egenskap bör skrivas ut på nästa sida. Standard falskt. |
| [setMinRowHeight](#setMinRowHeight-double-) | Hämtar höjd för raden. |
| [setRowBroken](#setRowBroken-boolean-) | Hämtar om raden kan brytas mellan två sidor. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Hämtar eller anger vertikal justering. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
konstruktör endast för internt bruk

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Skapar {@link TableTHElement} och lägger till den i den aktuella tabellen.

**Returns:**
Skapat strukturelement.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Skapar {@link TableTHElement} och lägger till den i den aktuella tabellen.

**Returns:**
Skapat strukturelement.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Hämtar eller anger radens bakgrundsfärg.

**Returns:**
Color-instans

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Hämtar eller anger radens kant.

**Returns:**
BorderInfo instans

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

Hämtar eller anger standardmarginal för radceller.

**Returns:**
MarginInfo instans

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Hämtar eller anger standardtexttillstånd för radceller.

**Returns:**
TextState-instans

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Hämtar fast radhöjd – raden kan ha fast höjd.

**Returns:**
double-värde

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Hämtar höjd för raden.

**Returns:**
double-värde

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Hämtar eller anger vertikal justering.

**Returns:**
VerticalAlignment-element

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Hämtar om fast rad är på en ny sida – sidan med denna egenskap bör skrivas ut på nästa sida. Standard falskt.

**Returns:**
booleskt värde

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Hämtar om raden kan brytas mellan två sidor.

**Returns:**
booleskt värde

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Hämtar eller anger radens bakgrundsfärg.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Hämtar eller anger radens kant.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Hämtar standardcellkant.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Hämtar eller anger standardmarginal för radceller.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Hämtar eller anger standardtexttillstånd för radceller.

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Hämtar fast radhöjd – raden kan ha fast höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Hämtar om fast rad är på en ny sida – sidan med denna egenskap bör skrivas ut på nästa sida. Standard falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Hämtar höjd för raden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Hämtar om raden kan brytas mellan två sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Hämtar eller anger vertikal justering.
