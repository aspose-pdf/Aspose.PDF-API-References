---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Tabelle dar, die auf der Seite existiert."
type: docs
weight: 30
url: /de/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Stellt eine Tabelle dar, die auf der Seite existiert.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Vergleicht das aktuelle AbsorbedTable‑Objekt mit einem anderen AbsorbedTable‑Objekt und gibt einen Integer zurück, der angibt, ob das aktuelle Objekt dem anderen vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge liegt. |
| [getPageNum](#getPageNum--) | Liefert die Seitennummer, die diese Tabelle enthält |
| [getRectangle](#getRectangle--) | Liefert das Rechteck, das die Position der Tabelle auf der Seite beschreibt |
| [getRowList](#getRowList--) | <p> Liefert eine schreibgeschützte IList, die die Zeilen der Tabelle enthält </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Vergleicht das aktuelle AbsorbedTable‑Objekt mit einem anderen AbsorbedTable‑Objekt und gibt einen Integer zurück, der angibt, ob das aktuelle Objekt dem anderen vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge liegt.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Liefert die Seitennummer, die diese Tabelle enthält

**Returns:**
int-Wert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das Rechteck, das die Position der Tabelle auf der Seite beschreibt

**Returns:**
Rectangle-Objekt

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Liefert eine schreibgeschützte IList, die die Zeilen der Tabelle enthält </p>

**Returns:**
{@code IGenericList<AbsorbedRow>}-Objekt
