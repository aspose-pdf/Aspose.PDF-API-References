---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una cella della tabella presente nella pagina"
type: docs
weight: 10
url: /it/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Rappresenta una cella della tabella presente nella pagina

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Confronta l'oggetto AbsorbedCell corrente con un altro oggetto AbsorbedCell e restituisce un intero che indica se l'oggetto corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto. |
| [getBorderInfo](#getBorderInfo--) | Restituisce le informazioni sul bordo della cella quando la proprietà FlowEngine.TableAbsorber.UseFlowEngine è impostata su true. |
| [getColSpan](#getColSpan--) | Restituisce il numero di colonne che la cella deve occupare quando la proprietà TableAbsorber.UseFlowEngine è impostata su true. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo che descrive la posizione della cella nella pagina |
| [getTextFragments](#getTextFragments--) | Ottiene la collezione di oggetti {@code TextFragment} che descrive il testo contenuto nella cella |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Confronta l'oggetto AbsorbedCell corrente con un altro oggetto AbsorbedCell e restituisce un intero che indica se l'oggetto corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento rispetto all'altro oggetto.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Restituisce le informazioni sul bordo della cella quando la proprietà FlowEngine.TableAbsorber.UseFlowEngine è impostata su true.

**Returns:**
Istanza BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Restituisce il numero di colonne che la cella deve occupare quando la proprietà TableAbsorber.UseFlowEngine è impostata su true.

**Returns:**
valore int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ottiene il rettangolo che descrive la posizione della cella nella pagina

**Returns:**
oggetto Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Ottiene la collezione di oggetti {@code TextFragment} che descrive il testo contenuto nella cella

**Returns:**
Oggetto TextFragmentCollection
