---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe rappresenta una collezione di operatori"
type: docs
weight: 3190
url: /it/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

La classe rappresenta una collezione di operatori

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Solo per uso interno! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Solo per uso interno! |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitatore IOperatorSelector per elaborare gli operatori. |
| [add](#add-java.lang.Iterable-) | Aggiunge alla collezione tutti gli operatori da un'altra collezione. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Aggiunge un nuovo operatore nella collezione. </p> <hr> <p> L'esempio dimostra come aggiungere operatori alla fine di page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Aggiunge operatori alla fine degli operatori di contenuto. </p> <hr> <p> L'esempio dimostra come aggiungere un operatore alla fine del contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto. |
| [clear](#clear--) | <p> Rimuove tutti gli operatori dall'elenco. </p> <hr> <p> L'esempio dimostra come cancellare il contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [contains](#contains-com.aspose.pdf.Operator-) | Restituisce true se la collezione contiene l'operatore specificato. |
| [delete](#delete-int-) | <p> Elimina l'operatore dalla collezione. </p> <hr> <p> L'esempio dimostra come eliminare un operatore tramite il suo indice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Elimina gli operatori dalla collezione. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Elimina gli operatori dalla collezione. </p> <hr> <p> L'esempio dimostra come rimuovere un operatore dal contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | versione interna non limitata di Delete(index) |
| [dispose](#dispose--) | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [get_Item](#get_Item-int-) | <p> Ottiene l'operatore tramite il suo indice. </p> <hr> L'esempio dimostra come ottenere l'operatore del contenuto della pagina tramite indice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Versione interna non limitata dell'indicizzatore |
| [insert](#insert-int-java.lang.Iterable-) | Inserisce operatori nella posizione specificata. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Inserisce un operatore nella collezione. </p> <hr> <p> L'esempio dimostra come inserire un operatore nel contenuto della pagina. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Inserisce operatori nella posizione specificata. </p> <hr> <p> L'esempio dimostra come inserire un operatore nel contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Ottiene lo stato di parentesizzazione della sequenza di operatori, cioè se questi operatori sono all'interno dei blocchi q - Q |
| [isCommandsParsed](#isCommandsParsed--) | Ottiene i comandi analizzati |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indica se la collezione è limitata all'estrazione rapida del testo |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [iterator](#iterator--) | Restituisce l'enumeratore per la collezione |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Ottiene il numero di operatori che descrivono il contenuto della pagina senza la loro inizializzazione. |
| [remove](#remove-com.aspose.pdf.Operator-) | Rimuove l'operatore dalla collezione. |
| [replace](#replace-java.lang.Iterable-) | Sostituisce gli operatori nella collezione con altri operatori. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Sostituisce gli operatori nella collezione con altri operatori. |
| [resumeUpdate](#resumeUpdate--) | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. |
| [resumeUpdate](#resumeUpdate-boolean-) | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. Contrassegna tutti gli operatori come "changed" se il parametro invalidate è true. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Imposta l'operatore per indice. |
| [size](#size--) | Ottiene il conteggio degli operatori nella collezione. |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento dei dati dei contenuti Lo stream dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate |
| [toList](#toList--) | Restituisce l'elenco degli operatori. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |
| [updateData](#updateData--) | Aggiorna lo stream dell'oggetto. |
| [updateNormalizedData](#updateNormalizedData--) | Aggiorna lo stream dell'oggetto correggendo gli operatori GSave/GRestore assenti. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Solo per uso interno!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Solo per uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitatore IOperatorSelector per elaborare gli operatori.

### add {#add-java.lang.Iterable-}
Aggiunge alla collezione tutti gli operatori da un'altra collezione.

### add {#add-com.aspose.pdf.Operator-}
<p> Aggiunge un nuovo operatore nella collezione. </p> <hr> <p> L'esempio dimostra come aggiungere operatori alla fine di page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Aggiunge operatori alla fine degli operatori di contenuto. </p> <hr> <p> L'esempio dimostra come aggiungere un operatore alla fine del contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto.

### clear {#clear--}
```
public void clear()
```

<p> Rimuove tutti gli operatori dall'elenco. </p> <hr> <p> L'esempio dimostra come cancellare il contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### contains {#contains-com.aspose.pdf.Operator-}
Restituisce true se la collezione contiene l'operatore specificato.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Elimina l'operatore dalla collezione. </p> <hr> <p> L'esempio dimostra come eliminare un operatore tramite il suo indice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'operatore da eliminare. La numerazione degli operatori inizia da 1. |

### delete {#delete-java.lang.Iterable-}
Elimina gli operatori dalla collezione.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Elimina gli operatori dalla collezione. </p> <hr> <p> L'esempio dimostra come rimuovere un operatore dal contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

versione interna non limitata di Delete(index)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

### dispose {#dispose--}
```
public final void dispose()
```

Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Ottiene l'operatore tramite il suo indice. </p> <hr> L'esempio dimostra come ottenere l'operatore del contenuto della pagina tramite indice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Versione interna non limitata dell'indicizzatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | valore int |

**Returns:**
Oggetto operatore

### insert {#insert-int-java.lang.Iterable-}
Inserisce operatori nella posizione specificata.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Inserisce un operatore nella collezione. </p> <hr> <p> L'esempio dimostra come inserire un operatore nel contenuto della pagina. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Inserisce operatori nella posizione specificata. </p> <hr> <p> L'esempio dimostra come inserire un operatore nel contenuto della pagina. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Ottiene lo stato di parentesizzazione della sequenza di operatori, cioè se questi operatori sono all'interno dei blocchi q - Q

**Returns:**
valore booleano

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Ottiene i comandi analizzati

**Returns:**
valore booleano

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Restituisce l'enumeratore per la collezione

**Returns:**
Enumeratore della collezione

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Ottiene il numero di operatori che descrivono il contenuto della pagina senza la loro inizializzazione.

**Returns:**
valore int

### remove {#remove-com.aspose.pdf.Operator-}
Rimuove l'operatore dalla collezione.

### replace {#replace-java.lang.Iterable-}
Sostituisce gli operatori nella collezione con altri operatori.

### replace {#replace-com.aspose.pdf.Operator:A-}
Sostituisce gli operatori nella collezione con altri operatori.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. Contrassegna tutti gli operatori come "changed" se il parametro invalidate è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| updateAll |  | Se true, tutti gli operatori nella collezione sono contrassegnati come aggiornati. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Imposta l'operatore per indice.

### size {#size--}
```
public int size()
```

Ottiene il conteggio degli operatori nella collezione.

**Returns:**
valore int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Sopprime l'aggiornamento dei dati dei contenuti Lo stream dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Restituisce l'elenco degli operatori.

**Returns:**
elenco degli operatori.

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

### updateData {#updateData--}
```
public void updateData()
```

Aggiorna lo stream dell'oggetto.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Aggiorna lo stream dell'oggetto correggendo gli operatori GSave/GRestore assenti.
