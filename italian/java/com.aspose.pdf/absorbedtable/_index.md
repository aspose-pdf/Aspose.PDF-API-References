---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la tabella presente nella pagina"
type: docs
weight: 30
url: /it/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Rappresenta la tabella presente nella pagina

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Confronta l'oggetto AbsorbedTable corrente con un altro oggetto AbsorbedTable e restituisce un intero che indica se l'oggetto corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto. |
| [getPageNum](#getPageNum--) | Restituisce il numero della pagina che contiene questa tabella |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo che descrive la posizione della tabella nella pagina |
| [getRowList](#getRowList--) | <p> Restituisce IList di sola lettura contenente le righe della tabella </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Confronta l'oggetto AbsorbedTable corrente con un altro oggetto AbsorbedTable e restituisce un intero che indica se l'oggetto corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Restituisce il numero della pagina che contiene questa tabella

**Returns:**
valore int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo che descrive la posizione della tabella nella pagina

**Returns:**
oggetto Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Restituisce IList di sola lettura contenente le righe della tabella </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} oggetto
