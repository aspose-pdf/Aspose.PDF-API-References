---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta la collezione di file incorporati."
type: docs
weight: 1200
url: /it/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Classe che rappresenta la collezione di file incorporati.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Aggiunge la specifica del file incorporato nella collezione. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Aggiunge il file ai file incorporati con la chiave specificata. |
| [clear](#clear--) | Rimuovi tutti i file incorporati dal documento. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Determina se la collezione contiene la specifica FileSpecification. Non supportato. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Copia l'array di oggetti FileSpecification nella collezione. |
| [delete](#delete--) | Rimuovi tutti i file incorporati dal documento. |
| [delete](#delete-java.lang.String-) | Rimuovi tutti i file incorporati dal documento. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Elimina il file dalla collezione tramite la sua chiave nella collezione. |
| [findByName](#findByName-java.lang.String-) | Restituisce il file incorporato per nome. |
| [get_Item](#get_Item-int-) | Ottiene il file incorporato per indice. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il file incorporato per nome. |
| [getKeys](#getKeys--) | Restituisce l'elenco delle chiavi degli allegati file. |
| [getSyncRoot](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa collezione. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Verifica se la struttura File incorporati esiste. Restituisce TRUE se la struttura esiste, e FALSE altrimenti. Se il documento non ha mai contenuto file incorporati, questa struttura non è stata creata ed è assente. |
| [isReadOnly](#isReadOnly--) | Determina se la collezione è di sola lettura. Restituisce sempre false. |
| [isSynchronized](#isSynchronized--) | Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Restituisce l'enumeratore della collezione. |
| [iterator](#iterator--) | Restituisce l'enumeratore della collezione. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Rimuove la FileSpecification specificata dalla collezione. Non supportato. |
| [size](#size--) | Ottiene il numero di file incorporati nella collezione. |

### add {#add-com.aspose.pdf.FileSpecification-}
Aggiunge la specifica del file incorporato nella collezione.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Aggiunge il file ai file incorporati con la chiave specificata.

### clear {#clear--}
```
public void clear()
```

Rimuovi tutti i file incorporati dal documento.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Determina se la collezione contiene la specifica FileSpecification. Non supportato.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Copia l'array di oggetti FileSpecification nella collezione.

### delete {#delete--}
```
public void delete()
```

Rimuovi tutti i file incorporati dal documento.

### delete {#delete-java.lang.String-}
Rimuovi tutti i file incorporati dal documento.

### deleteByKey {#deleteByKey-java.lang.String-}
Elimina il file dalla collezione tramite la sua chiave nella collezione.

### findByName {#findByName-java.lang.String-}
Restituisce il file incorporato per nome.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Ottiene il file incorporato per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice del file incorporato. La numerazione inizia da 1. |

**Returns:**
Specificazione del file incorporato recuperata

### get_Item {#get_Item-java.lang.String-}
Ottiene il file incorporato per nome.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Restituisce l'elenco delle chiavi degli allegati file.

**Returns:**
Elenco di valori String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa collezione.

**Returns:**
Oggetto per la sincronizzazione

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Verifica se la struttura File incorporati esiste. Restituisce TRUE se la struttura esiste, e FALSE altrimenti. Se il documento non ha mai contenuto file incorporati, questa struttura non è stata creata ed è assente.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determina se la collezione è di sola lettura. Restituisce sempre false.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Restituisce l'enumeratore della collezione.

**Returns:**
Enumeratore della collezione.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Restituisce l'enumeratore della collezione.

**Returns:**
Enumeratore della collezione.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Rimuove la FileSpecification specificata dalla collezione. Non supportato.

### size {#size--}
```
public int size()
```

Ottiene il numero di file incorporati nella collezione.

**Returns:**
valore int
