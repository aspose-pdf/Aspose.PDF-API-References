---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe rappresenta la raccolta di tutte le destinazioni (un albero di nomi che mappa stringhe di nome a destinazioni (vedi 12.3.2.3, \"Named Destinations\") e (vedi 7.7.4, \"Name Dictionary\")) in."
type: docs
weight: 960
url: /it/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Classe che rappresenta la raccolta di tutte le destinazioni (un albero di nomi che mappa stringhe di nome a destinazioni (vedi 12.3.2.3, \"Named Destinations\") e (vedi 7.7.4, \"Name Dictionary\")) nel documento pdf.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Aggiunge l'elemento specificato. |
| [clear](#clear--) | La raccolta è di sola lettura. Lancia sempre l'eccezione NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se questa istanza contiene l'oggetto. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia gli elementi della raccolta in un Array, iniziando da un indice specifico dell'Array. |
| [get_Item](#get_Item-int-) | Ottiene l'oggetto destinazione per indice. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Restituisce la destinazione esplicita per nome. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Restituisce il numero di pagina della destinazione per nome. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Restituisce l'indice della destinazione nella raccolta. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [iterator](#iterator--) | Restituisce l'enumeratore. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove l'elemento specificato. |
| [size](#size--) | Ottiene il numero di elementi contenuti nella raccolta. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Aggiunge l'elemento specificato.

### clear {#clear--}
```
public void clear()
```

La raccolta è di sola lettura. Lancia sempre l'eccezione NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se questa istanza contiene l'oggetto.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia gli elementi della raccolta in un Array, iniziando da un indice specifico dell'Array.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Ottiene l'oggetto destinazione per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice della destinazione da ottenere. |

**Returns:**
Destinazione.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Restituisce la destinazione esplicita per nome.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Restituisce il numero di pagina della destinazione per nome.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Restituisce l'indice della destinazione nella raccolta.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene un valore che indica se la collezione è di sola lettura.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Restituisce l'enumeratore.

**Returns:**
L'enumeratore.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove l'elemento specificato.

### size {#size--}
```
public int size()
```

Ottiene il numero di elementi contenuti nella raccolta.

**Returns:**
valore int
