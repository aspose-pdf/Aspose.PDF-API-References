---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per la manipolazione dei metadati XMP."
type: docs
weight: 620
url: /it/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Classe per la manipolazione dei metadati XMP.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Costruttore per PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Costruttore per PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Aggiunge un campo di estensione nei metadati. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Aggiunge un valore ai metadati XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Aggiunge una coppia con chiave e valore nel dizionario. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Aggiunge un nuovo elemento all'oggetto dizionario. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Aggiunge un nuovo elemento all'oggetto dizionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Rimuove tutti gli elementi dall'oggetto. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Verifica se il dizionario contiene la proprietà specificata. |
| [contains](#contains-java.lang.String-) | <p> Verifica se il dizionario contiene la chiave specificata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Verifica se la coppia chiave-valore specificata è contenuta nel dizionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina se questo dizionario contiene la chiave specificata. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia i metadati in un array. |
| [get_Item](#get_Item-java.lang.String-) | <p> Ottiene il valore per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Ottiene il valore dei metadati XMP per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Ottiene il dizionario dei campi di estensione. </p> |
| [getKeys](#getKeys--) | Ottiene le chiavi dal dizionario. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Ottiene l'URI dello spazio dei nomi per prefisso. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Ottiene il prefisso per URI dello spazio dei nomi. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Ottiene l'oggetto di sincronizzazione della collezione. |
| [getValues](#getValues--) | Ottiene la collezione di valori nel dizionario. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Ottiene lo XmpMetadata del PDF di input in formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Ottiene lo XmpMetadata del PDF di input in formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Restituisce true se la collezione ha dimensione fissa. |
| [isReadOnly](#isReadOnly--) | Restituisce true se la collezione è di sola lettura. |
| [isSynchronized](#isSynchronized--) | Restituisce true se la collezione è sincronizzata. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Ottiene l'oggetto enumeratore del dizionario. |
| [iteratorIt](#iteratorIt--) | Ottiene l'oggetto enumeratore della collezione. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Registra l'URI dello spazio dei nomi. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Rimuove la coppia chiave/valore dalla collezione. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Rimuove l'elemento con la chiave specificata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Rimuove la chiave dal dizionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Imposta il valore per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Imposta il valore dei metadati XMP per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Ottiene il conteggio degli elementi nella collezione. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Cerca di trovare la chiave nel dizionario e recupera il valore se trovata. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Costruttore per PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Costruttore per PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Aggiunge un campo di estensione nei metadati.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Aggiunge un valore ai metadati XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Aggiunge una coppia con chiave e valore nel dizionario.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Aggiunge un nuovo elemento all'oggetto dizionario.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Aggiunge un nuovo elemento all'oggetto dizionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Rimuove tutti gli elementi dall'oggetto. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Verifica se il dizionario contiene la proprietà specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà |  | Proprietà che sarà controllata. |

**Returns:**
True - se il dizionario contiene la proprietà specificata; altrimenti, false.

### contains {#contains-java.lang.String-}
<p> Verifica se il dizionario contiene la chiave specificata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Verifica se la coppia chiave-valore specificata è contenuta nel dizionario.

### containsKey {#containsKey-java.lang.String-}
Determina se questo dizionario contiene la chiave specificata.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia i metadati in un array.

### get_Item {#get_Item-java.lang.String-}
<p> Ottiene il valore per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Ottiene il valore dei metadati XMP per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key |  | Chiave del valore. |

**Returns:**
Valore dai metadati XMP. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Ottiene il dizionario dei campi di estensione. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} oggetto

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Ottiene le chiavi dal dizionario.

**Returns:**
Elemento ICollection

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Ottiene l'URI dello spazio dei nomi per prefisso. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Ottiene il prefisso per URI dello spazio dei nomi. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ottiene l'oggetto di sincronizzazione della collezione.

**Returns:**
Elemento Object

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Ottiene la collezione di valori nel dizionario.

**Returns:**
oggetto ICollection

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Ottiene lo XmpMetadata del PDF di input in formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
I byte di XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Ottiene lo XmpMetadata del PDF di input in formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
I byte di XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Restituisce true se la collezione ha dimensione fissa.

**Returns:**
valore booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Restituisce true se la collezione è di sola lettura.

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce true se la collezione è sincronizzata.

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

Ottiene l'oggetto enumeratore del dizionario.

**Returns:**
L'oggetto enumeratore.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Ottiene l'oggetto enumeratore della collezione.

**Returns:**
Oggetto IEnumerator

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Registra l'URI dello spazio dei nomi. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Rimuove la coppia chiave/valore dalla collezione.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Rimuove l'elemento con la chiave specificata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key |  | Chiave dell'elemento che sarà eliminato. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Rimuove la chiave dal dizionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Imposta il valore per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Imposta il valore dei metadati XMP per chiave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Ottiene il conteggio degli elementi nella collezione. </p>

**Returns:**
valore int <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Cerca di trovare la chiave nel dizionario e recupera il valore se trovata.
