---
title: "Metadati"
linktitle: "Metadati"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Fornisce l'accesso al flusso di metadati XMP."
type: docs
weight: 3050
url: /it/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Fornisce l'accesso al flusso di metadati XMP.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Aggiunge valore ai metadati. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Aggiunge l'estensione pdf ai metadati. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Aggiunge valore ai metadati. |
| [clear](#clear--) | Cancella i metadati. |
| [contains](#contains-java.lang.String-) | Verifica se la chiave è contenuta nei metadati. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Verifica se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina se questo dizionario contiene la chiave specificata. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Copia gli elementi della collezione in un array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia gli elementi della collezione in un array. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene i dati dai metadati. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Solo per uso interno. Ottiene il dizionario dei campi di estensione. |
| [getExtensionFields](#getExtensionFields--) | <p> Ottiene il dizionario dei campi di estensione. </p> |
| [getItem](#getItem-java.lang.String-) | Ottiene i dati dai metadati. |
| [getKeys](#getKeys--) | Ottiene la collezione delle chiavi dei metadati. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Restituisce l'URI dello spazio dei nomi per prefisso. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Restituisce il prefisso per l'URI dello spazio dei nomi. |
| [getSyncRoot](#getSyncRoot--) | Ottiene l'oggetto di sincronizzazione della collezione. |
| [getValues](#getValues--) | Ottiene i valori nei metadati. |
| [isFixedSize](#isFixedSize--) | Verifica se la collezione ha dimensione fissa. |
| [isReadOnly](#isReadOnly--) | Verifica se la collezione è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Verifica se la collezione è sincronizzata. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Restituisce l'enumeratore del dizionario. |
| [iteratorIE](#iteratorIE--) | Ottiene l'enumeratore della collezione. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registra l'URI dello spazio dei nomi. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registra l'URI dello spazio dei nomi. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove la coppia chiave/valore dalla collezione. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Rimuove la voce dai metadati. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Imposta i dati dai metadati. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Imposta i dati dai metadati. |
| [size](#size--) | Ottiene il conteggio degli elementi nella collezione. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovata. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovata. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Aggiunge una coppia con chiave e valore nel dizionario.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Aggiunge valore ai metadati.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Aggiunge l'estensione pdf ai metadati.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Aggiunge valore ai metadati.

### clear {#clear--}
```
public void clear()
```

Cancella i metadati.

### contains {#contains-java.lang.String-}
Verifica se la chiave è contenuta nei metadati.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Verifica se la coppia chiave-valore specificata è contenuta nel dizionario.

### containsKey {#containsKey-java.lang.String-}
Determina se questo dizionario contiene la chiave specificata.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Copia gli elementi della collezione in un array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia gli elementi della collezione in un array.

### get_Item {#get_Item-java.lang.String-}
Ottiene i dati dai metadati.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Solo per uso interno. Ottiene il dizionario dei campi di estensione.

**Returns:**
oggetto interno

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Ottiene il dizionario dei campi di estensione. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} oggetto

### getItem {#getItem-java.lang.String-}
Ottiene i dati dai metadati.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Ottiene la collezione delle chiavi dei metadati.

**Returns:**
oggetto ICollection

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Restituisce l'URI dello spazio dei nomi per prefisso.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Restituisce il prefisso per l'URI dello spazio dei nomi.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene l'oggetto di sincronizzazione della collezione.

**Returns:**
Oggetto per la sincronizzazione

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Ottiene i valori nei metadati.

**Returns:**
oggetto ICollection

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Verifica se la collezione ha dimensione fissa.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Verifica se la collezione è di sola lettura.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Verifica se la collezione è sincronizzata.

**Returns:**
valore booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Restituisce l'enumeratore del dizionario.

**Returns:**
Enumeratore.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Ottiene l'enumeratore della collezione.

**Returns:**
oggetto IEnumerator @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registra l'URI dello spazio dei nomi.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registra l'URI dello spazio dei nomi.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove la coppia chiave/valore dalla collezione.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Rimuove la voce dai metadati.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Imposta i dati dai metadati.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Imposta i dati dai metadati.

### size {#size--}
```
public int size()
```

Ottiene il conteggio degli elementi nella collezione.

**Returns:**
valore int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Cerca di trovare la chiave nel dizionario e recupera il valore se trovata.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Cerca di trovare la chiave nel dizionario e recupera il valore se trovata.
