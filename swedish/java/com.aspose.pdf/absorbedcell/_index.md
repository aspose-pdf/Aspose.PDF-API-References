---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en cell i en tabell som finns på sidan"
type: docs
weight: 10
url: /sv/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Representerar en cell i en tabell som finns på sidan

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Jämför det aktuella AbsorbedCell-objektet med ett annat AbsorbedCell-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet. |
| [getBorderInfo](#getBorderInfo--) | Returnerar kantinformation för cellen när egenskapen FlowEngine.TableAbsorber.UseFlowEngine är satt till true. |
| [getColSpan](#getColSpan--) | Returnerar antalet kolumner som cellen ska spänna över när egenskapen TableAbsorber.UseFlowEngine är satt till true. |
| [getRectangle](#getRectangle--) | Hämtar rektangel som beskriver cellens position på sidan |
| [getTextFragments](#getTextFragments--) | Hämtar samling av {@code TextFragment}-objekt som beskriver texten i cellen |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Jämför det aktuella AbsorbedCell-objektet med ett annat AbsorbedCell-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Returnerar kantinformation för cellen när egenskapen FlowEngine.TableAbsorber.UseFlowEngine är satt till true.

**Returns:**
BorderInfo instans

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Returnerar antalet kolumner som cellen ska spänna över när egenskapen TableAbsorber.UseFlowEngine är satt till true.

**Returns:**
int‑värde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangel som beskriver cellens position på sidan

**Returns:**
Rectangle‑objekt

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Hämtar samling av {@code TextFragment}-objekt som beskriver texten i cellen

**Returns:**
TextFragmentCollection-objekt
