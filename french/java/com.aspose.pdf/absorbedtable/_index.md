---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un tableau qui existe sur la page"
type: docs
weight: 30
url: /fr/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Représente un tableau qui existe sur la page

## Méthodes

| Méthode | Description |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Compare l'objet AbsorbedTable actuel avec un autre objet AbsorbedTable et renvoie un entier qui indique si l'objet actuel précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [getPageNum](#getPageNum--) | Obtient le numéro de la page contenant ce tableau |
| [getRectangle](#getRectangle--) | Obtient le rectangle qui décrit la position du tableau sur la page |
| [getRowList](#getRowList--) | <p> Obtient la IList en lecture seule contenant les lignes du tableau </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Compare l'objet AbsorbedTable actuel avec un autre objet AbsorbedTable et renvoie un entier qui indique si l'objet actuel précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Obtient le numéro de la page contenant ce tableau

**Returns:**
valeur int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle qui décrit la position du tableau sur la page

**Returns:**
objet Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Obtient la IList en lecture seule contenant les lignes du tableau </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} objet
