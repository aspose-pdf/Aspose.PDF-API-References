---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta BoundsCheckableList - wrapper attorno a System.Collections.Generic.List."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Rappresenta BoundsCheckableList - wrapper attorno a System.Collections.Generic.List.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Inizializza una nuova istanza della classe BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Inizializza una nuova istanza della classe BoundsCheckableList. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addItem](#addItem-T-) | Aggiunge un oggetto alla fine di System.Collections.Generic.List in base al parametro "boundsCheckMode". |
| [clear](#clear--) | Rimuove tutti gli elementi da System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Determina se un elemento è presente in System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Copia l'intera System.Collections.Generic.List in un array monodimensionale compatibile, a partire dall'indice specificato dell'array di destinazione. |
| [get_Item](#get_Item-int-) | Ottiene o imposta il paragrafo dalla o nella collezione. |
| [indexOfItem](#indexOfItem-T-) | Cerca l'oggetto specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Inserisce un elemento in System.Collections.Generic.List all'indice specificato. |
| [isReadOnly](#isReadOnly--) | Ottiene il valore che indica se la collezione è di sola lettura. |
| [iterator](#iterator--) | Restituisce un enumeratore che itera attraverso System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Rimuove l'elemento all'indice specificato della System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Rimuove la prima occorrenza di un oggetto specifico dalla System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Ottiene o imposta il paragrafo dalla o nella collezione. |
| [size](#size--) | Restituisce il numero di elementi contenuti nella System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Aggiorna il parametro boundsCheckMode per la collezione inizializzata. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Aggiorna il parametro boundsCheckMode per la collezione inizializzata. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Inizializza una nuova istanza della classe BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Inizializza una nuova istanza della classe BoundsCheckableList.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| boundsCheckMode |  | La bounds cCheck mode. |
| containerWidth |  | La larghezza del contenitore. |
| containerHeight |  | L'altezza del contenitore. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Aggiunge un oggetto alla fine di System.Collections.Generic.List in base al parametro "boundsCheckMode".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item |  | L'oggetto da aggiungere alla fine della System.Collections.Generic.List. Il valore può essere "null" per i tipi di riferimento. |

### clear {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi da System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Determina se un elemento è presente in System.Collections.Generic.List.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item |  | L'oggetto da individuare nella System.Collections.Generic.List. Il valore può essere null per i tipi di riferimento. |

**Returns:**
true se itemitem è trovato nella System.Collections.Generic.List; altrimenti, false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Copia l'intera System.Collections.Generic.List in un array monodimensionale compatibile, a partire dall'indice specificato dell'array di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array |  | Il System.Array monodimensionale che è la destinazione degli elementi copiati dalla System.Collections.Generic.List. Il System.Array deve avere un indice basato su zero. |
| arrayIndex |  | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Ottiene o imposta il paragrafo dalla o nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice del paragrafo. |

**Returns:**
l'elemento all'indice specificato.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Cerca l'oggetto specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera System.Collections.Generic.List.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item |  | L'oggetto da individuare nella System.Collections.Generic.List. Il valore può essere null per i tipi di riferimento. |

**Returns:**
L'indice basato su zero della prima occorrenza di itemitem all'interno dell'intera System.Collections.Generic.List, se trovato; altrimenti, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Inserisce un elemento in System.Collections.Generic.List all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice basato su zero al quale l'item dovrebbe essere inserito. |
| item |  | L'oggetto da inserire. Il valore può essere null per i tipi di riferimento. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene il valore che indica se la collezione è di sola lettura.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Restituisce un enumeratore che itera attraverso System.Collections.Generic.List.

**Returns:**
Un enumeratore per la System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della System.Collections.Generic.List.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice basato su zero dell'elemento da rimuovere. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Rimuove la prima occorrenza di un oggetto specifico dalla System.Collections.Generic.List.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item |  | L'oggetto da rimuovere dalla System.Collections.Generic.List. Il valore può essere null per i tipi di riferimento. |

**Returns:**
true se itemitem è stato rimosso con successo; altrimenti, false. Questo metodo restituisce anche false se itemitem non è stato trovato nella System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Ottiene o imposta il paragrafo dalla o nella collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice del paragrafo. |

### size {#size--}
```
public final int size()
```

Restituisce il numero di elementi contenuti nella System.Collections.Generic.List.

**Returns:**
Il numero di elementi contenuti nella System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Aggiorna il parametro boundsCheckMode per la collezione inizializzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| boundsCheckMode |  | La modalità di controllo dei limiti. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Aggiorna il parametro boundsCheckMode per la collezione inizializzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| boundsCheckMode |  | La modalità di controllo dei limiti. |
| containerWidth |  | La larghezza del contenitore. |
| containerHeight |  | L'altezza del contenitore. |
