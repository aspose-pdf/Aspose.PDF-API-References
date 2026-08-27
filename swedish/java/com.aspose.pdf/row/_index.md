---
title: "Row"
linktitle: "Row"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en rad i tabellen."
type: docs
weight: 4330
url: /sv/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Representerar en rad i tabellen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Row](#Row--) | Initierar en ny instans av klassen Row. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klona raden. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar bakgrundsfärgen. |
| [getBorder](#getBorder--) | Hämtar kanten. |
| [getCells](#getCells--) | Hämtar getCells() för raden. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Hämtar standardcellram; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Hämtar standardmarginal för rad getCells() |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Hämtar eller anger standardtexttillstånd för rad getCells() Hämtar standardtexttillstånd för rad getCells() |
| [getFixedRowHeight](#getFixedRowHeight--) | Hämtar fast radhöjd – raden kan ha fast höjd; |
| [getMinRowHeight](#getMinRowHeight--) | Hämtar höjd för raden; |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar eller anger vertikal justering. |
| [isInNewPage](#isInNewPage--) | Hämtar om fast rad är på ny sida – sida med denna egenskap bör skrivas ut på nästa sida Standard falskt; |
| [isRowBroken](#isRowBroken--) | Hämtar om raden kan brytas mellan två sidor |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ställer in bakgrundsfärgen. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Anger kanten. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Ställer in getCells() för raden. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Ställer in standardcellram; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Ställer in standardmarginal för radens getCells() |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Ställer in standardtexttillstånd för radens getCells() |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Ställer in fast radhöjd - raden kan ha fast höjd; |
| [setInNewPage](#setInNewPage-boolean-) | Ställer in om raden kan brytas mellan två sidor |
| [setMinRowHeight](#setMinRowHeight-double-) | Ställer in höjd för raden; |
| [setRowBroken](#setRowBroken-boolean-) | Ställer in om raden kan brytas mellan två sidor |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Hämtar eller anger vertikal justering. |

### Row {#Row--}
```
public Row()
```

Initierar en ny instans av klassen Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona raden.

**Returns:**
Det klonade objektet

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Hämtar bakgrundsfärgen.

**Returns:**
Färgvärde

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Hämtar kanten.

**Returns:**
BorderInfo‑värde

### getCells {#getCells--}
```
public Cells getCells()
```

Hämtar getCells() för raden.

**Returns:**
getCells()‑värde

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Hämtar standardcellram;

**Returns:**
BorderInfo‑värde

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Hämtar standardmarginal för rad getCells()

**Returns:**
MarginInfo‑värde

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Hämtar eller anger standardtexttillstånd för rad getCells() Hämtar standardtexttillstånd för rad getCells()

**Returns:**
TextState värde

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Hämtar fast radhöjd – raden kan ha fast höjd;

**Returns:**
double-värde

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Hämtar höjd för raden;

**Returns:**
double-värde

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar eller anger vertikal justering.

**Returns:**
VerticalAlignment-element @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Hämtar om fast rad är på ny sida – sida med denna egenskap bör skrivas ut på nästa sida Standard falskt;

**Returns:**
booleskt värde

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Hämtar om raden kan brytas mellan två sidor

**Returns:**
booleskt värde

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ställer in bakgrundsfärgen.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Anger kanten.

### setCells {#setCells-com.aspose.pdf.Cells-}
Ställer in getCells() för raden.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Ställer in standardcellram;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Ställer in standardmarginal för radens getCells()

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Ställer in standardtexttillstånd för radens getCells()

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Ställer in fast radhöjd - raden kan ha fast höjd;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Ställer in om raden kan brytas mellan två sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Ställer in höjd för raden;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Ställer in om raden kan brytas mellan två sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Hämtar eller anger vertikal justering.
