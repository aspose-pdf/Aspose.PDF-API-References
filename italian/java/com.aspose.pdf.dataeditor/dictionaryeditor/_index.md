---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe per accedere al dizionario ad albero di un documento (dizionario del documento, dizionario della pagina, dizionario delle risorse)."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Una classe per accedere al dizionario ad albero di un documento (dizionario del documento, dizionario della pagina, dizionario delle risorse).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Le risorse sono nulle. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Imposta ICosPdfPrimitive nel dizionario. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Imposta {@link ICosPdfPrimitive} nel dizionario. |
| [clear](#clear--) | Rimuove tutti gli elementi dal {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determina se il DictionaryEditor contiene un valore specifico. |
| [containsKey](#containsKey-java.lang.String-) | Determina se il {@link DictionaryEditor} contiene un elemento con la chiave specificata. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia gli elementi del DictionaryEditor in un Array, a partire da un indice specifico dell'Array. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene o imposta l'elemento con la chiave specificata. |
| [getAllKeys](#getAllKeys--) | Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili. |
| [getKeys](#getKeys--) | Raccolta di chiavi modificabili. |
| [getValues](#getValues--) | Ottiene un {@link ICollection} contenente i valori nel {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Ottiene un valore che indica se il {@link DictionaryEditor} è di sola lettura. |
| [iterator](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove la prima occorrenza di un oggetto specifico dal DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Rimuove l'elemento con la chiave specificata dal {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ottiene o imposta l'elemento con la chiave specificata. |
| [size](#size--) | Ottiene il numero di elementi contenuti nel {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Per accedere a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Le risorse sono nulle.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Imposta ICosPdfPrimitive nel dizionario.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Imposta {@link ICosPdfPrimitive} nel dizionario.

### clear {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dal {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determina se il DictionaryEditor contiene un valore specifico.

### containsKey {#containsKey-java.lang.String-}
Determina se il {@link DictionaryEditor} contiene un elemento con la chiave specificata.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia gli elementi del DictionaryEditor in un Array, a partire da un indice specifico dell'Array.

### get_Item {#get_Item-java.lang.String-}
Ottiene o imposta l'elemento con la chiave specificata.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Raccolta completa di chiavi. Contiene chiavi modificabili e non modificabili.

**Returns:**
Iterabile di istanza String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Raccolta di chiavi modificabili.

**Returns:**
Iterabile di istanza String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Ottiene un {@link ICollection} contenente i valori nel {@link DictionaryEditor}.

**Returns:**
Iterabile di istanza ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene un valore che indica se il {@link DictionaryEditor} è di sola lettura.

**Returns:**
vero se il {@link DictionaryEditor} è di sola lettura; altrimenti, falso.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
Un enumeratore che può essere usato per iterare attraverso la collezione.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove la prima occorrenza di un oggetto specifico dal DictionaryEditor.

### remove {#remove-java.lang.String-}
Rimuove l'elemento con la chiave specificata dal {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ottiene o imposta l'elemento con la chiave specificata.

### size {#size--}
```
public final int size()
```

Ottiene il numero di elementi contenuti nel {@link DictionaryEditor}.

**Returns:**
valore int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Per accedere a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi.
