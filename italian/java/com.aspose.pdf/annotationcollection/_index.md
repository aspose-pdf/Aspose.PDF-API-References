---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta una collezione di annotazioni."
type: docs
weight: 80
url: /it/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Classe che rappresenta una collezione di annotazioni.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Costruttore di AnnotationCollection. Crea una collezione di annotazioni per le annotazioni nella pagina fornita. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un visitatore per elaborare l'annotazione. |
| [add](#add-com.aspose.pdf.Annotation-) | Aggiunge l'annotazione alla collezione. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Aggiunge l'annotazione alla collezione. Se la pagina è ruotata, il rettangolo dell'annotazione verrà ricalcolato di conseguenza. |
| [clear](#clear--) | Elimina tutte le annotazioni dalla collezione. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Verifica se l'annotazione specificata appartiene alla collezione. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Copia l'array di annotazioni nella collezione. |
| [delete](#delete--) | Elimina tutte le annotazioni dalla collezione. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Elimina tutte le annotazioni dalla collezione. |
| [delete](#delete-int-) | Elimina l'annotazione dalla collezione per indice. |
| [findByName](#findByName-java.lang.String-) | Restituisce l'annotazione per nome. |
| [get_Item](#get_Item-int-) | L'indice dell'elemento da ottenere. |
| [getSyncRoot](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso a com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è in sola lettura. |
| [isSynchronized](#isSynchronized--) | Ottiene un valore che indica se l'accesso a com.aspose.pdf.AnnotationCollection è sincronizzato (thread‑safe). |
| [iterator](#iterator--) | Restituisce l'enumeratore della collezione. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Elimina l'annotazione specificata dalla collezione. |
| [size](#size--) | Ottiene il conteggio delle annotazioni nella collezione. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Costruttore di AnnotationCollection. Crea una collezione di annotazioni per le annotazioni nella pagina fornita.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un visitatore per elaborare l'annotazione.

### add {#add-com.aspose.pdf.Annotation-}
Aggiunge l'annotazione alla collezione.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Aggiunge l'annotazione alla collezione. Se la pagina è ruotata, il rettangolo dell'annotazione verrà ricalcolato di conseguenza.

### clear {#clear--}
```
public void clear()
```

Elimina tutte le annotazioni dalla collezione.

### contains {#contains-com.aspose.pdf.Annotation-}
Verifica se l'annotazione specificata appartiene alla collezione.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Copia l'array di annotazioni nella collezione.

### delete {#delete--}
```
public void delete()
```

Elimina tutte le annotazioni dalla collezione.

### delete {#delete-com.aspose.pdf.Annotation-}
Elimina tutte le annotazioni dalla collezione.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina l'annotazione dalla collezione per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'annotazione da eliminare. |

### findByName {#findByName-java.lang.String-}
Restituisce l'annotazione per nome.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

L'indice dell'elemento da ottenere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Il valore dell'indice inizia da uno. |

**Returns:**
Oggetto annotazione

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene un oggetto che può essere usato per sincronizzare l'accesso a com.aspose.pdf.AnnotationCollection.

**Returns:**
Oggetto per la sincronizzazione

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene un valore che indica se la collezione è in sola lettura.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ottiene un valore che indica se l'accesso a com.aspose.pdf.AnnotationCollection è sincronizzato (thread‑safe).

**Returns:**
valore booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Restituisce l'enumeratore della collezione.

**Returns:**
Oggetto enumeratore

### remove {#remove-com.aspose.pdf.Annotation-}
Elimina l'annotazione specificata dalla collezione.

### size {#size--}
```
public int size()
```

Ottiene il conteggio delle annotazioni nella collezione.

**Returns:**
valore int
