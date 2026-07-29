---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina."
type: docs
weight: 150
url: /it/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Aggiunge un elemento con la chiave e il valore forniti. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Aggiungi il modulo X per la chiave specificata. |
| [clear](#clear--) | Rimuove tutti gli elementi dal dizionario. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Verifica se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina se questo dizionario contiene la chiave specificata. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Restituisce un oggetto IDictionaryEnumerator per il dizionario. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia gli elementi dell'ICollection in un Array, iniziando da un indice specifico dell'Array. |
| [get_Item](#get_Item-java.lang.String-) | Rappresenta una forma conveniente per ottenere i flussi di aspetto. |
| [getDict](#getDict--) | Ottiene il dizionario pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state valori, dove N - aspetto normale, R - aspetto rollover, D - aspetto premuto e state - il nome dello stato (ad es. On, Off per le caselle di controllo). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state valori, dove N - aspetto normale, R - aspetto rollover, D - aspetto premuto e state - il nome dello stato (ad es. On, Off per le caselle di controllo). |
| [getSyncRoot](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso al dizionario. |
| [getValues_](#getValues_--) | Ottiene l'elenco dei valori del dizionario. La collezione risultante contiene l'elenco di oggetti XForm. |
| [getValues](#getValues--) | Ottiene l'elenco dei valori del dizionario. La collezione risultante contiene l'elenco di oggetti XForm. |
| [isFixedSize](#isFixedSize--) | Ottiene un valore che indica se il dizionario ha una dimensione fissa. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se il dizionario è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Ottiene un valore che indica se l'accesso al dizionario è sincronizzato (thread safe). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumeratore per la collezione. |
| [iterator](#iterator--) | Restituisce un oggetto IDictionaryEnumerator per il dizionario. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove la coppia chiave/valore dalla collezione. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Rimuove la chiave dal dizionario. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Ottiene il numero di elementi contenuti nel dizionario. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovata. |

### add {#add-java.lang.Object-java.lang.Object-}
Aggiunge un elemento con la chiave e il valore forniti.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Aggiunge una coppia con chiave e valore nel dizionario.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Aggiungi il modulo X per la chiave specificata.

### clear {#clear--}
```
public void clear()
```

Rimuove tutti gli elementi dal dizionario.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Verifica se la coppia chiave-valore specificata è contenuta nel dizionario.

### containsKey {#containsKey-java.lang.String-}
Determina se questo dizionario contiene la chiave specificata.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Restituisce un oggetto IDictionaryEnumerator per il dizionario. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia gli elementi dell'ICollection in un Array, iniziando da un indice specifico dell'Array.

### get_Item {#get_Item-java.lang.String-}
Rappresenta una forma conveniente per ottenere i flussi di aspetto.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Ottiene il dizionario pdf

**Returns:**
oggetto IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Ottiene le chiavi del dizionario. Se il dizionario di aspetto ha sottodizionari, allora {@code Keys} contiene valori (N|R|D).state, dove N - aspetto normale, R - aspetto rollover, D - aspetto premuto e state - il nome dello stato (ad es. On, Off per le caselle di controllo).

**Returns:**
Elenco di valori String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Ottiene le chiavi del dizionario. Se il dizionario di aspetto ha sottodizionari, allora {@code Keys} contiene valori (N|R|D).state, dove N - aspetto normale, R - aspetto rollover, D - aspetto premuto e state - il nome dello stato (ad es. On, Off per le caselle di controllo).

**Returns:**
Elenco di valori String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene un oggetto che può essere usato per sincronizzare l'accesso al dizionario.

**Returns:**
Oggetto per la sincronizzazione

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Ottiene l'elenco dei valori del dizionario. La collezione risultante contiene l'elenco di oggetti XForm.

**Returns:**
Elenco di valori XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Ottiene l'elenco dei valori del dizionario. La collezione risultante contiene l'elenco di oggetti XForm.

**Returns:**
Elenco di valori XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Ottiene un valore che indica se il dizionario ha una dimensione fissa.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ottiene un valore che indica se il dizionario è di sola lettura.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ottiene un valore che indica se l'accesso al dizionario è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumeratore per la collezione.

**Returns:**
enumeratore degli elementi della collezione.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Restituisce un oggetto IDictionaryEnumerator per il dizionario.

**Returns:**
Enumeratore del dizionario.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove la coppia chiave/valore dalla collezione.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Rimuove la chiave dal dizionario.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Ottiene il numero di elementi contenuti nel dizionario.

**Returns:**
valore int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Cerca di trovare la chiave nel dizionario e recupera il valore se trovata.
