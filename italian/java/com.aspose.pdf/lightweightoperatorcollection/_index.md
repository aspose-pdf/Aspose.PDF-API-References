---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Collezione di operatori leggera. Destinata a essere usata in scenari in cui lo stream dei contenuti sottostante non è allegato, dove è richiesta solo la collezione di operatori come risultato."
type: docs
weight: 2700
url: /it/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Collezione di operatori leggera. Destinata a essere usata in scenari in cui lo stream dei contenuti sottostante non è allegato, dove è richiesta solo la collezione di operatori come risultato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Inizializza l'oggetto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Inizializza l'oggetto |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Inizializza l'oggetto |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Aggiungi operatore |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Aggiungi LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto. |
| [clear](#clear--) | Cancella la collezione. |
| [contains](#contains-com.aspose.pdf.Operator-) | Verifica se l'elemento è nella collezione. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | elimina interno Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Ottiene l'operatore per il suo indice. </p> <hr> <pre> L'esempio dimostra come ottenere l'operatore del contenuto della pagina per indice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Per uso interno l'operatore getUnrestricted |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Inserisci operatore |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se la collezione è limitata all'estrazione rapida del testo |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [iterator](#iterator--) | Restituisci iteratore |
| [remove](#remove-com.aspose.pdf.Operator-) | Rimuove l'operatore dalla collezione. |
| [resumeUpdate](#resumeUpdate--) | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Imposta l'operatore per il suo indice. <hr> <pre> L'esempio dimostra come ottenere l'operatore del contenuto della pagina per indice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Conteggio operatori |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento dei dati di contenuto. Il flusso di contenuto non viene aggiornato finché non viene chiamato ResumeUpdate. |
| [toList](#toList--) | Restituisce l'elenco degli operatori. |
| [updateData](#updateData--) | internal |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Inizializza l'oggetto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Inizializza l'oggetto

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Inizializza l'oggetto

### add {#add-com.aspose.pdf.Operator-}
Aggiungi operatore

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Aggiungi LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto.

### clear {#clear--}
```
public void clear()
```

Cancella la collezione.

### contains {#contains-com.aspose.pdf.Operator-}
Verifica se l'elemento è nella collezione.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

elimina interno Unrestrictedelement

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Ottiene l'operatore per il suo indice. </p> <hr> <pre> L'esempio dimostra come ottenere l'operatore del contenuto della pagina per indice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'operatore. La numerazione inizia da 1. |

**Returns:**
Operatore dall'indice richiesto

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Per uso interno l'operatore getUnrestricted

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

**Returns:**
Oggetto operatore

### insert {#insert-int-com.aspose.pdf.Operator-}
Inserisci operatore

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indica se la collezione è limitata all'estrazione rapida del testo

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene un valore che indica se la collezione è di sola lettura.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Restituisci iteratore

**Returns:**
{@code IGenericEnumerator<Operator>} oggetto

### remove {#remove-com.aspose.pdf.Operator-}
Rimuove l'operatore dalla collezione.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Imposta l'operatore per il suo indice. <hr> <pre> L'esempio dimostra come ottenere l'operatore del contenuto della pagina per indice. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Conteggio operatori

**Returns:**
valore int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Sopprime l'aggiornamento dei dati di contenuto. Il flusso di contenuto non viene aggiornato finché non viene chiamato ResumeUpdate.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Restituisce l'elenco degli operatori.

**Returns:**
elenco degli operatori.

### updateData {#updateData--}
```
public void updateData()
```

internal
