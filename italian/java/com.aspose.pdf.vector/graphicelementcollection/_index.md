---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la collezione {@link GraphicElement}."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Rappresenta la collezione {@link GraphicElement}.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Inizializza la nuova collezione. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Aggiunge un nuovo {@link GraphicElement} alla collezione. Tutti gli elementi nella collezione devono avere lo stesso {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Svuota la collezione. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Determina se un elemento è nella collezione. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Copia l'intera collezione in un Array monodimensionale compatibile, a partire dall'indice specificato dell'array di destinazione. |
| [get_Item](#get_Item-int-) | Restituisce l'elemento {@link GraphicElement} all'indice specificato. |
| [isReadOnly](#isReadOnly--) | Restituisce un valore che indica se la collezione è di sola lettura. Restituisce sempre false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Restituisce un enumeratore per l'intera collezione. |
| [iterator](#iterator--) | Restituisce un enumeratore per l'intera collezione. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Elimina l'elemento {@link GraphicElement}. |
| [size](#size--) | Restituisce il numero di oggetti {@link GraphicElement} effettivamente contenuti nella collezione. |
| [toList](#toList--) | Restituisce la collezione interna per l'enumerazione non limitata. |
| [toString](#toString--) | Ottiene una rappresentazione stringa di questa collezione. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Inizializza la nuova collezione.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Aggiunge un nuovo {@link GraphicElement} alla collezione. Tutti gli elementi nella collezione devono avere lo stesso {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Svuota la collezione.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Determina se un elemento è nella collezione.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Copia l'intera collezione in un Array monodimensionale compatibile, a partire dall'indice specificato dell'array di destinazione.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Restituisce l'elemento {@link GraphicElement} all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice nella collezione. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce un valore che indica se la collezione è di sola lettura. Restituisce sempre false.

**Returns:**
valore booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Elimina l'elemento {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Restituisce il numero di oggetti {@link GraphicElement} effettivamente contenuti nella collezione.

**Returns:**
valore int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Restituisce la collezione interna per l'enumerazione non limitata.

**Returns:**
Elenco interno

### toString {#toString--}
```
public String toString()
```

Ottiene una rappresentazione stringa di questa collezione.

**Returns:**
La stringa.
