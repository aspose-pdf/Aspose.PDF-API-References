---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe per accedere al dizionario di un oggetto."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Una classe per accedere al dizionario di un oggetto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Crea un dizionario dalle risorse. @exception ArgumentNullException Le risorse sono null. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Imposta ICosPdfPrimitive nel dizionario. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Imposta {@link ICosPdfPrimitive} nel dizionario. @exception ArgumentException Lancia un'eccezione se la chiave/valore non può essere modificata o rimossa. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Aggiungi coppia di elementi. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Aggiungi elemento. |
| [clear](#clear--) | Rimuove tutti gli elementi dal {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se il CosPdfDictionary contiene un valore specifico. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Restituisce true se contiene l'elemento |
| [containsKey](#containsKey-java.lang.String-) | Determina se il {@link CosPdfDictionary} contiene un elemento con la chiave specificata. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia gli elementi del CosPdfDictionary in un Array, iniziando da un indice specifico dell'Array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia in Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Crea un dizionario vuoto che sarà allegato al documento. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Crea un dizionario vuoto che verrà allegato alla pagina. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene o imposta l'elemento con la chiave specificata. |
| [getAllKeys](#getAllKeys--) | Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili. |
| [getKeys](#getKeys--) | Raccolta di chiavi modificabili. |
| [getValues](#getValues--) | Ottiene una {@link ICollection} contenente i valori nel {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se il {@link CosPdfDictionary} è di sola lettura. |
| [iterator](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove la prima occorrenza di un oggetto specifico dal CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Rimuove l'elemento con la chiave specificata dal {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuovi elemento |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Rimuovi elemento per chiave. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ottiene o imposta l'elemento con la chiave specificata. @exception ArgumentNullException La chiave è null. @exception KeyNotFoundException La proprietà è recuperata e la chiave non è stata trovata. @exception ArgumentException Lancia un'eccezione se la chiave non può essere modificata/impostata. |
| [size](#size--) | Ottiene il numero di elementi contenuti nel {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Prova a castare questa istanza a {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Per accedere a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Prova a ottenere il valore |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Crea un dizionario dalle risorse. @exception ArgumentNullException Le risorse sono null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Imposta ICosPdfPrimitive nel dizionario.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Imposta {@link ICosPdfPrimitive} nel dizionario. @exception ArgumentException Lancia un'eccezione se la chiave/valore non può essere modificata o rimossa.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Aggiungi coppia di elementi.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Aggiungi elemento.

### clear {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dal {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se il CosPdfDictionary contiene un valore specifico.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Restituisce true se contiene l'elemento

### containsKey {#containsKey-java.lang.String-}
Determina se il {@link CosPdfDictionary} contiene un elemento con la chiave specificata.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia gli elementi del CosPdfDictionary in un Array, iniziando da un indice specifico dell'Array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia in Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Crea un dizionario vuoto che sarà allegato al documento.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Crea un dizionario vuoto che verrà allegato alla pagina.

### get_Item {#get_Item-java.lang.String-}
Ottiene o imposta l'elemento con la chiave specificata.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili.

**Returns:**
Elenco di valori String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Raccolta di chiavi modificabili.

**Returns:**
Elenco di valori String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Ottiene una {@link ICollection} contenente i valori nel {@link CosPdfDictionary}.

**Returns:**
Elenco di istanze ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene un valore che indica se il {@link CosPdfDictionary} è di sola lettura.

**Returns:**
true se il {@link CosPdfDictionary} è di sola lettura; altrimenti, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
Un enumeratore che può essere usato per iterare attraverso la collezione.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove la prima occorrenza di un oggetto specifico dal CosPdfDictionary.

### remove {#remove-java.lang.String-}
Rimuove l'elemento con la chiave specificata dal {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuovi elemento

### removeItemByKey {#removeItemByKey-java.lang.String-}
Rimuovi elemento per chiave.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ottiene o imposta l'elemento con la chiave specificata. @exception ArgumentNullException La chiave è null. @exception KeyNotFoundException La proprietà è recuperata e la chiave non è stata trovata. @exception ArgumentException Lancia un'eccezione se la chiave non può essere modificata/impostata.

### size {#size--}
```
public final int size()
```

Ottiene il numero di elementi contenuti nel {@link CosPdfDictionary}.

**Returns:**
valore int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Prova a castare questa istanza a {@link CosPdfDictionary}.

**Returns:**
null se l'istanza non è {@link CosPdfDictionary} altrimenti {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Per accedere a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Prova a ottenere il valore
