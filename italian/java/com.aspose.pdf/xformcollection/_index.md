---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta la raccolta di XFormCollection."
type: docs
weight: 5600
url: /it/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Classe che rappresenta la raccolta di XFormCollection.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Aggiunge un nuovo XForm alla collezione. |
| [clear](#clear--) | Cancella tutti gli elementi dalla collezione. |
| [contains](#contains-com.aspose.pdf.XForm-) | Determina se la collezione contiene un valore specifico. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Copia XFormCollection nella collezione. |
| [delete](#delete--) | Elimina tutti gli XForm dalla collezione. |
| [delete](#delete-int-) | Elimina XForm dalla collezione |
| [delete](#delete-java.lang.String-) | Elimina tutti gli XForm dalla collezione. |
| [freeMemory](#freeMemory--) | Cancella i dati nella cache, libera la memoria ecc. |
| [get_Item](#get_Item-int-) | Restituisce XForm per indice. |
| [get_Item](#get_Item-java.lang.String-) | Restituisce XForm per nome. Viene sollevata un'eccezione se XForm con il nome specificato non viene trovato. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Restituisce il nome del form in questa collezione di form |
| [getSyncRoot](#getSyncRoot--) | Oggetto di sincronizzazione. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Restituisce true se l'oggetto è sincronizzato. |
| [iterator](#iterator--) | Restituisce l'enumeratore della collezione. |
| [remove](#remove-com.aspose.pdf.XForm-) | Elimina l'elemento specificato dalla raccolta. |
| [size](#size--) | Ottiene il conteggio degli XForm nella collezione. |

### add {#add-com.aspose.pdf.XForm-}
Aggiunge un nuovo XForm alla collezione.

### clear {#clear--}
```
public void clear()
```

Cancella tutti gli elementi dalla collezione.

### contains {#contains-com.aspose.pdf.XForm-}
Determina se la collezione contiene un valore specifico.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Copia XFormCollection nella collezione.

### delete {#delete--}
```
public void delete()
```

Elimina tutti gli XForm dalla collezione.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina XForm dalla collezione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'XForm da eliminare |

### delete {#delete-java.lang.String-}
Elimina tutti gli XForm dalla collezione.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Cancella i dati nella cache, libera la memoria ecc.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Restituisce XForm per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice di XFormCollection. La numerazione degli XForm inizia da 1 |

**Returns:**
XForm recuperato

### get_Item {#get_Item-java.lang.String-}
Restituisce XForm per nome. Viene sollevata un'eccezione se XForm con il nome specificato non viene trovato.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Restituisce il nome del form in questa collezione di form

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Oggetto di sincronizzazione.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


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

Restituisce true se l'oggetto è sincronizzato.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Restituisce l'enumeratore della collezione.

**Returns:**
Enumeratore per la collezione

### remove {#remove-com.aspose.pdf.XForm-}
Elimina l'elemento specificato dalla raccolta.

### size {#size--}
```
public int size()
```

Ottiene il conteggio degli XForm nella collezione.

**Returns:**
valore int
