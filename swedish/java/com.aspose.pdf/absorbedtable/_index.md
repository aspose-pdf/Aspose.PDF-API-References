---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en tabell som finns på sidan"
type: docs
weight: 30
url: /sv/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Representerar en tabell som finns på sidan

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Jämför det aktuella AbsorbedTable-objektet med ett annat AbsorbedTable-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet. |
| [getPageNum](#getPageNum--) | Hämtar sidnumret för sidan som innehåller denna tabell |
| [getRectangle](#getRectangle--) | Hämtar rektangeln som beskriver tabellens position på sidan |
| [getRowList](#getRowList--) | <p> Hämtar readonly IList som innehåller raderna i tabellen </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Jämför det aktuella AbsorbedTable-objektet med ett annat AbsorbedTable-objekt och returnerar ett heltal som indikerar om det aktuella objektet föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Hämtar sidnumret för sidan som innehåller denna tabell

**Returns:**
int‑värde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln som beskriver tabellens position på sidan

**Returns:**
Rectangle‑objekt

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Hämtar readonly IList som innehåller raderna i tabellen </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} objekt
