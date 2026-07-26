---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la raccolta di caratteri. </p> <hr> <pre> L'esempio dimostra come rendere tutti i font dichiarati nella pagina incorporati. // Open document Document doc = new.</pre>"
type: docs
weight: 1670
url: /it/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Rappresenta la raccolta di caratteri. </p> <hr> <pre> L'esempio dimostra come rendere tutti i font dichiarati nella pagina incorporati. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Le raccolte di font rappresentate dalla classe {@code FontCollection} sono utilizzate in diversi scenari. Per esempio, nelle risorse con la proprietà {@code Resources.Fonts}. </p>

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Aggiunge Font alla raccolta. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Aggiunge un nuovo font alle risorse dei font e restituisce il nome assegnato automaticamente alla risorsa del font. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Aggiungi un nuovo font alla raccolta di font. |
| [add](#add-java.lang.String-java.lang.String-) | Aggiunge alle risorse dei font una nuova voce di font con il nome base del font specificato. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Aggiunge Font alla raccolta. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Determina se la collezione contiene un valore specifico. |
| [contains](#contains-java.lang.String-) | Verifica se il font esiste nella raccolta di font. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione. |
| [delete](#delete-java.lang.String-) | Elimina Font con il nome risorsa specificato |
| [get_Item](#get_Item-int-) | Ottiene l'elemento font all'indice specificato. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il font dalla raccolta per nome del font. Viene sollevata un'eccezione se il font non è stato trovato. |
| [getFontsDictionary](#getFontsDictionary--) | Ottieni l'oggetto IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione. |
| [isReadOnly](#isReadOnly--) | Restituisce un valore che indica se la collezione è di sola lettura |
| [isSynchronized](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Restituisce un enumeratore per l'intera collezione. |
| [iterator](#iterator--) | Restituisce un enumeratore per l'intera collezione. |
| [remove](#remove-com.aspose.pdf.Font-) | Elimina l'elemento specificato dalla raccolta. |
| [size](#size--) | Restituisce il numero di elementi oggetto {@code Font} effettivamente contenuti nella raccolta. |

### add {#add-com.aspose.pdf.Font-}
Aggiunge Font alla raccolta.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Aggiunge un nuovo font alle risorse dei font e restituisce il nome assegnato automaticamente alla risorsa del font.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Aggiungi un nuovo font alla raccolta di font.

### add {#add-java.lang.String-java.lang.String-}
Aggiunge alle risorse dei font una nuova voce di font con il nome base del font specificato.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Aggiunge Font alla raccolta. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Determina se la collezione contiene un valore specifico.

### contains {#contains-java.lang.String-}
Verifica se il font esiste nella raccolta di font.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione.

### delete {#delete-java.lang.String-}
Elimina Font con il nome risorsa specificato

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Ottiene l'elemento font all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice nella collezione. |

**Returns:**
Oggetto Font.

### get_Item {#get_Item-java.lang.String-}
Ottiene il font dalla raccolta per nome del font. Viene sollevata un'eccezione se il font non è stato trovato.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Ottieni l'oggetto IPdfDictionary

**Returns:**
oggetto IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione.

**Returns:**
Oggetto per la sincronizzazione

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Restituisce un valore che indica se la collezione è di sola lettura

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### remove {#remove-com.aspose.pdf.Font-}
Elimina l'elemento specificato dalla raccolta.

### size {#size--}
```
public int size()
```

Restituisce il numero di elementi oggetto {@code Font} effettivamente contenuti nella raccolta.

**Returns:**
valore int
