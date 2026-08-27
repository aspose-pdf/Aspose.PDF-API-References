---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe base per la collezione di operatori."
type: docs
weight: 270
url: /it/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Rappresenta la classe base per la collezione di operatori.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Aggiunge un nuovo operatore alla collezione. |
| [cancelUpdate](#cancelUpdate--) | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto. |
| [clear](#clear--) | Cancella la collezione. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica se l'elemento è nella collezione. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internal |
| [get_Item](#get_Item-int-) | Ottiene l'operatore per il suo indice. |
| [getUnrestricted](#getUnrestricted-int-) | Solo per uso interno |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Inserisce l'operatore nella collezione. |
| [isEmpty](#isEmpty--) | Restituisce TRUE se la collezione è vuota. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se la collezione è limitata all'estrazione rapida del testo |
| [isReadOnly](#isReadOnly--) | Restituisce true se la collezione è di sola lettura. |
| [iterator](#iterator--) | Restituisce l'enumeratore per la collezione |
| [remove](#remove-com.aspose.pdf.Operator-) | Rimuove l'operatore dalla collezione. |
| [resumeUpdate](#resumeUpdate--) | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Imposta l'operatore per indice. |
| [size](#size--) | Ottiene il conteggio degli operatori nella collezione. |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento dei dati di contenuto. Il flusso di contenuto non viene aggiornato finché non viene chiamato ResumeUpdate. |
| [toList](#toList--) | Restituisce l'elenco degli operatori. |
| [updateData](#updateData--) | internal |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Aggiunge un nuovo operatore alla collezione.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto.

### clear {#clear--}
```
public abstract void clear()
```

Cancella la collezione.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica se l'elemento è nella collezione.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

internal

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Ottiene l'operatore per il suo indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'operatore. La numerazione inizia da 1. |

**Returns:**
Operatore dall'indice richiesto

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Solo per uso interno

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

**Returns:**
Oggetto operatore

### insert {#insert-int-com.aspose.pdf.Operator-}
Inserisce l'operatore nella collezione.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Restituisce TRUE se la collezione è vuota.

**Returns:**
valore booleano

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indica se la collezione è limitata all'estrazione rapida del testo

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Restituisce true se la collezione è di sola lettura.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Restituisce l'enumeratore per la collezione

**Returns:**
Enumeratore della collezione

### remove {#remove-com.aspose.pdf.Operator-}
Rimuove l'operatore dalla collezione.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Imposta l'operatore per indice.

### size {#size--}
```
public abstract int size()
```

Ottiene il conteggio degli operatori nella collezione.

**Returns:**
valore intero

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Sopprime l'aggiornamento dei dati di contenuto. Il flusso di contenuto non viene aggiornato finché non viene chiamato ResumeUpdate.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Restituisce l'elenco degli operatori.

**Returns:**
elenco degli operatori.

### updateData {#updateData--}
```
public abstract void updateData()
```

internal
