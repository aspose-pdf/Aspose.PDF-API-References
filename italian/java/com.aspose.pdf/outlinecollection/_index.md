---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la gerarchia del sommario del documento."
type: docs
weight: 3260
url: /it/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Rappresenta la gerarchia del sommario del documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Aggiunge un elemento di outline alla collezione. |
| [clear](#clear--) | Cancella tutti gli elementi dalla collezione. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Non ancora supportato. Verifica se la collezione contiene l'elemento specificato. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copia gli elementi di outline in un System.Array, iniziando da un indice specifico del System.Array. |
| [delete](#delete--) | Elimina tutti gli elementi di outline dall'indice del documento. |
| [delete](#delete-java.lang.String-) | Elimina tutti gli elementi di outline dall'indice del documento. |
| [get_Item](#get_Item-int-) | Ottiene l'elemento di outline dalla collezione per indice. |
| [getFirst](#getFirst--) | Ottiene un elemento di outline che rappresenta il primo elemento di livello superiore nell'outline. |
| [getLast](#getLast--) | Ottiene un elemento di outline che rappresenta l'ultimo elemento di livello superiore nell'outline. |
| [getSyncRoot](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa collezione. |
| [getVisibleCount](#getVisibleCount--) | Count è la somma del numero di elementi di outline discendenti visibili a tutti i livelli. Nota: per favore non confondere con Count che è il numero di elementi nella collezione. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [iterator](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [next](#next--) |  |
| [remove](#remove-int-) | Rimuove l'elemento per indice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Non ancora supportato. Lancia sempre un'eccezione. |
| [size](#size--) | Ottiene il numero totale di elementi di outline (segnalibri) a tutti i livelli dell'outline del documento. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Aggiunge un elemento di outline alla collezione.

### clear {#clear--}
```
public void clear()
```

Cancella tutti gli elementi dalla collezione.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Non ancora supportato. Verifica se la collezione contiene l'elemento specificato.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copia gli elementi di outline in un System.Array, iniziando da un indice specifico del System.Array.

### delete {#delete--}
```
public void delete()
```

Elimina tutti gli elementi di outline dall'indice del documento.

### delete {#delete-java.lang.String-}
Elimina tutti gli elementi di outline dall'indice del documento.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Ottiene l'elemento di outline dalla collezione per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'elemento richiesto. |

**Returns:**
OutlineItemCollection object

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Ottiene un elemento di outline che rappresenta il primo elemento di livello superiore nell'outline.

**Returns:**
OutlineItemCollection object

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Ottiene un elemento di outline che rappresenta l'ultimo elemento di livello superiore nell'outline.

**Returns:**
OutlineItemCollection object

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa collezione.

**Returns:**
Oggetto per la sincronizzazione

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count è la somma del numero di elementi di outline discendenti visibili a tutti i livelli. Nota: per favore non confondere con Count che è il numero di elementi nella collezione.

**Returns:**
valore int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene un valore che indica se la collezione è di sola lettura.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
Un oggetto System.Collections.IEnumerator che può essere usato per iterare attraverso la collezione.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Rimuove l'elemento per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'elemento da rimuovere. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Non ancora supportato. Lancia sempre un'eccezione.

### size {#size--}
```
public int size()
```

Ottiene il numero totale di elementi di outline (segnalibri) a tutti i livelli dell'outline del documento.

**Returns:**
valore int
