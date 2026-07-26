---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Zelle einer Tabelle dar, die auf der Seite existiert."
type: docs
weight: 10
url: /de/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Stellt eine Zelle einer Tabelle dar, die auf der Seite existiert.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Vergleicht das aktuelle AbsorbedCell-Objekt mit einem anderen AbsorbedCell-Objekt und gibt eine Ganzzahl zurück, die angibt, ob das aktuelle Objekt dem anderen vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge wie das andere Objekt steht. |
| [getBorderInfo](#getBorderInfo--) | Gibt die Randinformationen für die Zelle zurück, wenn die Eigenschaft FlowEngine.TableAbsorber.UseFlowEngine auf true gesetzt ist. |
| [getColSpan](#getColSpan--) | Gibt die Anzahl der Spalten zurück, die die Zelle überspannen soll, wenn die Eigenschaft TableAbsorber.UseFlowEngine auf true gesetzt ist. |
| [getRectangle](#getRectangle--) | Liefert das Rechteck, das die Position der Zelle auf der Seite beschreibt |
| [getTextFragments](#getTextFragments--) | Liefert eine Sammlung von {@code TextFragment}-Objekten, die den in der Zelle enthaltenen Text beschreiben |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Vergleicht das aktuelle AbsorbedCell-Objekt mit einem anderen AbsorbedCell-Objekt und gibt eine Ganzzahl zurück, die angibt, ob das aktuelle Objekt dem anderen vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge wie das andere Objekt steht.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Gibt die Randinformationen für die Zelle zurück, wenn die Eigenschaft FlowEngine.TableAbsorber.UseFlowEngine auf true gesetzt ist.

**Returns:**
BorderInfo‑Instanz

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Gibt die Anzahl der Spalten zurück, die die Zelle überspannen soll, wenn die Eigenschaft TableAbsorber.UseFlowEngine auf true gesetzt ist.

**Returns:**
int-Wert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das Rechteck, das die Position der Zelle auf der Seite beschreibt

**Returns:**
Rectangle-Objekt

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Liefert eine Sammlung von {@code TextFragment}-Objekten, die den in der Zelle enthaltenen Text beschreiben

**Returns:**
TextFragmentCollection-Objekt
