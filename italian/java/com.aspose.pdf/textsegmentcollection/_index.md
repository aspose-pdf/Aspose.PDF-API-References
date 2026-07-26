---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una raccolta di segmenti di testo"
type: docs
weight: 5310
url: /it/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

Rappresenta una raccolta di segmenti di testo

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | Aggiunge l'elemento segmento di testo all'indice specificato. |
| [clear](#clear--) | Cancella tutti gli elementi dalla collezione. |
| [contains](#contains-com.aspose.pdf.TextSegment-) | Determina se la collezione contiene un valore specifico. |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione. |
| [delete](#delete-int-) | Elimina l'elemento del segmento di testo all'indice specificato. |
| [get_Item](#get_Item-int-) | Ottiene l'elemento del segmento di testo all'indice specificato. |
| [getSyncRoot](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione. |
| [isReadOnly](#isReadOnly--) | Restituisce un valore che indica se la collezione è di sola lettura |
| [isSynchronized](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe). |
| [iterator](#iterator--) | Restituisce un enumeratore per l'intera collezione. |
| [remove](#remove-com.aspose.pdf.TextSegment-) | Elimina l'elemento specificato dalla raccolta. |
| [size](#size--) | Ottiene il numero di elementi oggetto {@code TextSegment} effettivamente contenuti nella collezione. |

### add {#add-com.aspose.pdf.TextSegment-}
Aggiunge l'elemento segmento di testo all'indice specificato.

### clear {#clear--}
```
public void clear()
```

Cancella tutti gli elementi dalla collezione.

### contains {#contains-com.aspose.pdf.TextSegment-}
Determina se la collezione contiene un valore specifico.

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina l'elemento del segmento di testo all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

Ottiene l'elemento del segmento di testo all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice nella collezione. |

**Returns:**
Oggetto TextSegment.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione.

**Returns:**
Elemento Object

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Restituisce un valore che indica se la collezione è di sola lettura

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator {#iterator--}
```
public Iterator < TextSegment > iterator()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### remove {#remove-com.aspose.pdf.TextSegment-}
Elimina l'elemento specificato dalla raccolta.

### size {#size--}
```
public int size()
```

Ottiene il numero di elementi oggetto {@code TextSegment} effettivamente contenuti nella collezione.

**Returns:**
valore int
