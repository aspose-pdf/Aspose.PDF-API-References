---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Collezione di pagine di documenti PDF."
type: docs
weight: 3340
url: /it/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Collezione di pagine di documenti PDF.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta l'oggetto visitatore {@code AnnotationSelector} che fornisce funzionalità per lavorare con le annotazioni. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accetta l'oggetto visitor {@code ImagePlacementAbsorber} che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accetta l'oggetto visitor {@code TextAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accetta l'oggetto visitor {@code TextFragmentAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Aggiunge una pagina alla collezione. |
| [add](#add--) | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [add](#add-java.lang.Iterable-) | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [add](#add-java.util.List-) | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [add](#add-com.aspose.pdf.Page-) | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [add](#add-com.aspose.pdf.Page:A-) | Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [beginUpdate](#beginUpdate--) | Aggiorna quando iniziano le modifiche di gruppo. |
| [clear](#clear--) | Cancella la collezione di pagine. |
| [contains](#contains-com.aspose.pdf.Page-) | Determina se questa istanza contiene l'oggetto. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Copia le pagine nel documento. |
| [delete](#delete--) | Elimina tutte le pagine dalla collezione. |
| [delete](#delete-int-) | Elimina la pagina specificata. |
| [delete](#delete-java.lang.Integer:A-) | Elimina tutte le pagine dalla collezione. |
| [endUpdate](#endUpdate--) | Aggiorna quando le modifiche di gruppo sono complete. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Rimuove tutti i campi presenti sulle pagine e ne colloca i valori al loro posto. |
| [freeMemory](#freeMemory--) | Cancella i dati memorizzati nella cache |
| [get_Item](#get_Item-int-) | Ottiene la pagina per indice. |
| [getSyncRoot](#getSyncRoot--) | Ottiene l'oggetto di sincronizzazione della collezione. |
| [getUnrestricted](#getUnrestricted-int-) | Restituisce la pagina per il suo indice. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Restituisce l'indice della pagina specificata. </p> |
| [insert](#insert-int-) | Inserisce una pagina vuota nella collezione nella posizione specificata. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina. |
| [insert](#insert-int-java.lang.Iterable-) | Inserisce pagine dalla collezione nel documento. |
| [insert](#insert-int-java.util.List-) | Inserisce pagine dalla collezione nel documento. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Inserisce una pagina nella collezione di pagine nel punto specificato. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Inserisce le pagine dell'array nel documento. |
| [isEmpty](#isEmpty--) | Restituisce TRUE se la collezione è vuota. |
| [isReadOnly](#isReadOnly--) | Ottiene il valore che indica se la collezione è di sola lettura. Restituisce sempre false. |
| [isSynchronized](#isSynchronized--) | Restituisce true se l'oggetto è sincronizzato. |
| [iterator](#iterator--) | Restituisce l'enumeratore delle pagine. |
| [remove](#remove-com.aspose.pdf.Page-) | Rimuove l'elemento specificato, genera un'eccezione. |
| [size](#size--) | Ottiene il conteggio delle pagine nel documento. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta l'oggetto visitatore {@code AnnotationSelector} che fornisce funzionalità per lavorare con le annotazioni.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accetta l'oggetto visitor {@code ImagePlacementAbsorber} che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accetta l'oggetto visitor {@code TextAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accetta l'oggetto visitor {@code TextFragmentAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Aggiunge una pagina alla collezione.

### add {#add--}
```
public Page add()
```

Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Returns:**
Pagina aggiunta.

### add {#add-java.lang.Iterable-}
Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Returns:**
Pagina aggiunta.

### add {#add-java.util.List-}
Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Returns:**
Pagina aggiunta.

### add {#add-com.aspose.pdf.Page-}
Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Returns:**
Pagina aggiunta.

### add {#add-com.aspose.pdf.Page:A-}
Aggiunge una pagina vuota. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Returns:**
Pagina aggiunta.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Aggiorna quando iniziano le modifiche di gruppo.

### clear {#clear--}
```
public void clear()
```

Cancella la collezione di pagine.

### contains {#contains-com.aspose.pdf.Page-}
Determina se questa istanza contiene l'oggetto.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Copia le pagine nel documento.

### delete {#delete--}
```
public void delete()
```

Elimina tutte le pagine dalla collezione.

### delete {#delete-int-}
```
public void delete(int index)
```

Elimina la pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Numero della pagina che verrà eliminata. I numeri delle pagine iniziano da 1. |

### delete {#delete-java.lang.Integer:A-}
Elimina tutte le pagine dalla collezione.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Aggiorna quando le modifiche di gruppo sono complete.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Rimuove tutti i campi presenti sulle pagine e ne colloca i valori al loro posto.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Cancella i dati memorizzati nella cache

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Ottiene la pagina per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice della pagina. |

**Returns:**
Pagina recuperata.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene l'oggetto di sincronizzazione della collezione.

**Returns:**
Oggetto per la sincronizzazione

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Restituisce la pagina per il suo indice. {@code Page}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice della pagina richiesta. Le pagine sono numerate a partire da 1. |

**Returns:**
Pagina richiesta

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Restituisce l'indice della pagina specificata. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Inserisce una pagina vuota nella collezione nella posizione specificata. Se il documento contiene già pagine di dimensioni variabili, verrà selezionata la dimensione della pagina più frequente. Nel caso ci siano solo due pagine diverse, verrà usata la dimensione della prima pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Posizione della nuova pagina. |

**Returns:**
Pagina inserita.

### insert {#insert-int-java.lang.Iterable-}
Inserisce pagine dalla collezione nel documento.

### insert {#insert-int-java.util.List-}
Inserisce pagine dalla collezione nel documento.

### insert {#insert-int-com.aspose.pdf.Page-}
Inserisce una pagina nella collezione di pagine nel punto specificato.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Inserisce le pagine dell'array nel documento.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Restituisce TRUE se la collezione è vuota.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene il valore che indica se la collezione è di sola lettura. Restituisce sempre false.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce true se l'oggetto è sincronizzato.

**Returns:**
valore booleano

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Restituisce l'enumeratore delle pagine.

**Returns:**
Enumeratore delle pagine

### remove {#remove-com.aspose.pdf.Page-}
Rimuove l'elemento specificato, genera un'eccezione.

### size {#size--}
```
public int size()
```

Ottiene il conteggio delle pagine nel documento.

**Returns:**
valore int
