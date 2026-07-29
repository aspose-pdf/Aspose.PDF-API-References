---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una voce del sommario nella gerarchia del sommario di un documento PDF."
type: docs
weight: 3270
url: /it/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Rappresenta una voce del sommario nella gerarchia del sommario di un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Inizializza una nuova istanza di questa classe utilizzando l'oggetto di voce di outline interno del motore. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Inizializza l'istanza dell'elemento di outline usando l'oggetto di gerarchia radice. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Aggiunge un elemento di outline alla collezione. |
| [clear](#clear--) | Cancella tutti gli elementi dalla collezione. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Non ancora supportato. Lancia sempre NotImplementedException |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copia le voci di outline in un System.Array, iniziando da un indice specifico di System.Array. |
| [delete](#delete--) | Elimina questo elemento di outline dalla gerarchia di outline del documento. |
| [delete](#delete-java.lang.String-) | Elimina questo elemento di outline dalla gerarchia di outline del documento. |
| [get_Item](#get_Item-int-) | Ottiene l'elemento di outline dalla collezione usando l'indice. |
| [getAction](#getAction--) | Ottiene l'azione per questo elemento di outline. |
| [getBold](#getBold--) | Ottiene il flag grassetto per il testo del titolo di questo elemento di outline |
| [getColor](#getColor--) | Ottiene il colore per il testo del titolo di questo elemento di outline. |
| [getDestination](#getDestination--) | Ottiene la destinazione per questo elemento di outline. |
| [getEngineDict](#getEngineDict--) | Solo interno |
| [getEngineObj](#getEngineObj--) | Solo interno |
| [getFirst](#getFirst--) | Ottiene l'elemento di outline che rappresenta il primo elemento di livello superiore nella gerarchia di outline. |
| [getItalic](#getItalic--) | Ottiene un flag corsivo per il testo del titolo di questo elemento di outline |
| [getLast](#getLast--) | Ottiene l'elemento di outline che rappresenta l'ultimo elemento di livello superiore nella gerarchia di outline. |
| [getLevel](#getLevel--) | Ottiene il livello di gerarchia dell'elemento di outline. |
| [getNext](#getNext--) | Ottiene l'elemento di outline che rappresenta l'elemento successivo rispetto a questo nella gerarchia di outline. |
| [getOpen](#getOpen--) | Ottieni lo stato di apertura (true/false) per l'elemento di outline. |
| [getParent](#getParent--) | Ottiene l'oggetto padre di questo elemento di outline nella gerarchia di outline. |
| [getPrev](#getPrev--) | Ottiene l'elemento di outline che rappresenta l'elemento precedente rispetto a questo nella gerarchia di outline. |
| [getSyncRoot](#getSyncRoot--) | Ottiene l'oggetto che può essere usato per sincronizzare l'accesso a questa collezione. |
| [getTitle](#getTitle--) | Ottiene il titolo per questo elemento di outline. |
| [getVisibleCount](#getVisibleCount--) | Ottiene il numero totale di elementi di outline a tutti i livelli nella gerarchia di outline del documento. |
| [hasNext](#hasNext--) | Verifica se l'outline item che rappresenta l'elemento successivo è relativo a questo elemento nella gerarchia dell'outline. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Inserisce l'outline item nella collezione nella posizione specificata. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se la collezione è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Ottiene il valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [iterator](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [next](#next--) |  |
| [remove](#remove-int-) | Rimuove l'elemento per indice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Non ancora supportato. Lancia sempre NotImplementedException |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Imposta l'azione per questo outline item. |
| [setBold](#setBold-boolean-) | Imposta il flag grassetto per il testo del titolo di questo outline item. |
| [setColor](#setColor-java.awt.Color-) | Imposta il colore per il testo del titolo di questo outline item. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Imposta la destinazione per questo outline item. |
| [setItalic](#setItalic-boolean-) | Imposta il flag corsivo per il testo del titolo di questo outline item. |
| [setOpen](#setOpen-boolean-) | Imposta lo stato di apertura (true/false) per l'outline item. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo per questo outline item. |
| [size](#size--) | Conteggio degli elementi della collezione. Per favore non confondere con VisibleCount: VisibleCount restituisce il numero di outline item visibili su tutti i livelli. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Inizializza una nuova istanza di questa classe utilizzando l'oggetto di voce di outline interno del motore.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Inizializza l'istanza dell'elemento di outline usando l'oggetto di gerarchia radice.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Aggiunge un elemento di outline alla collezione.

### clear {#clear--}
```
public void clear()
```

Cancella tutti gli elementi dalla collezione.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Non ancora supportato. Lancia sempre NotImplementedException

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copia le voci di outline in un System.Array, iniziando da un indice specifico di System.Array.

### delete {#delete--}
```
public void delete()
```

Elimina questo elemento di outline dalla gerarchia di outline del documento.

### delete {#delete-java.lang.String-}
Elimina questo elemento di outline dalla gerarchia di outline del documento.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Ottiene l'elemento di outline dalla collezione usando l'indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice nella collezione. |

**Returns:**
Oggetto OutlineItemCollection.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Ottiene l'azione per questo elemento di outline.

**Returns:**
Valore PdfAction

### getBold {#getBold--}
```
public boolean getBold()
```

Ottiene il flag grassetto per il testo del titolo di questo elemento di outline

**Returns:**
valore booleano

### getColor {#getColor--}
```
public Color getColor()
```

Ottiene il colore per il testo del titolo di questo elemento di outline.

**Returns:**
Valore colore

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Ottiene la destinazione per questo elemento di outline.

**Returns:**
valore IAppointment

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Solo interno

**Returns:**
oggetto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo interno

**Returns:**
Oggetto IPdfObject

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Ottiene l'elemento di outline che rappresenta il primo elemento di livello superiore nella gerarchia di outline.

**Returns:**
Valore OutlineItemCollection

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Ottiene un flag corsivo per il testo del titolo di questo elemento di outline

**Returns:**
valore booleano

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Ottiene l'elemento di outline che rappresenta l'ultimo elemento di livello superiore nella gerarchia di outline.

**Returns:**
Valore OutlineItemCollection

### getLevel {#getLevel--}
```
public int getLevel()
```

Ottiene il livello di gerarchia dell'elemento di outline.

**Returns:**
valore int

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Ottiene l'elemento di outline che rappresenta l'elemento successivo rispetto a questo nella gerarchia di outline.

**Returns:**
Valore OutlineItemCollection

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Ottieni lo stato di apertura (true/false) per l'elemento di outline.

**Returns:**
valore booleano

### getParent {#getParent--}
```
public Outlines getParent()
```

Ottiene l'oggetto padre di questo elemento di outline nella gerarchia di outline.

**Returns:**
Valore Object

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Ottiene l'elemento di outline che rappresenta l'elemento precedente rispetto a questo nella gerarchia di outline.

**Returns:**
Valore OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene l'oggetto che può essere usato per sincronizzare l'accesso a questa collezione.

**Returns:**
Valore Object

### getTitle {#getTitle--}
```
public String getTitle()
```

Ottiene il titolo per questo elemento di outline.

**Returns:**
valore String

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Ottiene il numero totale di elementi di outline a tutti i livelli nella gerarchia di outline del documento.

**Returns:**
valore int

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Verifica se l'outline item che rappresenta l'elemento successivo è relativo a questo elemento nella gerarchia dell'outline.

**Returns:**
valore booleano

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Inserisce l'outline item nella collezione nella posizione specificata.

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

Ottiene il valore che indica se l'accesso a questa collezione è sincronizzato (thread safe).

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
| index |  | Indice dell'elemento da eliminare. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Non ancora supportato. Lancia sempre NotImplementedException

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Imposta l'azione per questo outline item.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Imposta il flag grassetto per il testo del titolo di questo outline item.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setColor {#setColor-java.awt.Color-}
Imposta il colore per il testo del titolo di questo outline item.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Imposta la destinazione per questo outline item.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Imposta il flag corsivo per il testo del titolo di questo outline item.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Imposta lo stato di apertura (true/false) per l'outline item.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo per questo outline item.

### size {#size--}
```
public int size()
```

Conteggio degli elementi della collezione. Per favore non confondere con VisibleCount: VisibleCount restituisce il numero di outline item visibili su tutti i livelli.

**Returns:**
valore int
