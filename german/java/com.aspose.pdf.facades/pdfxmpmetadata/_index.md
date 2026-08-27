---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zur Manipulation von XMP-Metadaten."
type: docs
weight: 620
url: /de/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Klasse zur Manipulation von XMP-Metadaten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Konstruktor für PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Konstruktor für PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Fügt ein Erweiterungsfeld zu den Metadaten hinzu. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Fügt einen Wert zu XMP-Metadaten hinzu. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Fügt ein neues Element zum Wörterbuchobjekt hinzu. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Fügt dem Wörterbuchobjekt ein neues Element hinzu. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Entfernt alle Elemente aus dem Objekt. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Überprüft, ob das Wörterbuch die angegebene Eigenschaft enthält. |
| [contains](#contains-java.lang.String-) | <p> Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [containsKey](#containsKey-java.lang.String-) | Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Metadaten in ein Array kopieren. |
| [get_Item](#get_Item-java.lang.String-) | <p> Ermittelt den Wert nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Ermittelt den Wert der XMP-Metadaten nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Gibt das Wörterbuch der Erweiterungsfelder zurück. </p> |
| [getKeys](#getKeys--) | Ermittelt Schlüssel aus dem Wörterbuch. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Gibt den Namespace-URI nach Präfix zurück. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Gibt das Präfix nach Namespace-URI zurück. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Ermittelt das Synchronisationsobjekt der Sammlung. |
| [getValues](#getValues--) | Ermittelt die Sammlung von Werten im Wörterbuch. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Ruft die XmpMetadata der Eingabe‑PDF im XML-Format ab. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Ruft die XmpMetadata der Eingabe‑PDF im XML-Format ab. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Gibt true zurück, wenn die Sammlung eine feste Größe hat. |
| [isReadOnly](#isReadOnly--) | Gibt true zurück, wenn die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn die Sammlung synchronisiert ist. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Ermittelt das Enumerator‑Objekt des Wörterbuchs. |
| [iteratorIt](#iteratorIt--) | Ermittelt das Enumerator‑Objekt der Sammlung. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Registriert den Namespace-URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Entfernt das Element mit dem angegebenen Schlüssel. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Entfernt den Schlüssel aus dem Wörterbuch. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Setzt den Wert nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Setzt den Wert der XMP-Metadaten nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Gibt die Anzahl der Elemente in der Sammlung zurück. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Konstruktor für PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Konstruktor für PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Fügt ein Erweiterungsfeld zu den Metadaten hinzu.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Fügt einen Wert zu XMP-Metadaten hinzu. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Fügt ein neues Element zum Wörterbuchobjekt hinzu.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Fügt dem Wörterbuchobjekt ein neues Element hinzu. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Entfernt alle Elemente aus dem Objekt. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Überprüft, ob das Wörterbuch die angegebene Eigenschaft enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft |  | Eigenschaft, die überprüft wird. |

**Returns:**
True - wenn das Wörterbuch die angegebene Eigenschaft enthält; andernfalls false.

### contains {#contains-java.lang.String-}
<p> Überprüft, ob das Wörterbuch den angegebenen Schlüssel enthält. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist.

### containsKey {#containsKey-java.lang.String-}
Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Metadaten in ein Array kopieren.

### get_Item {#get_Item-java.lang.String-}
<p> Ermittelt den Wert nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Ermittelt den Wert der XMP-Metadaten nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel |  | Schlüssel des Werts. |

**Returns:**
Wert aus XMP-Metadaten. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Gibt das Wörterbuch der Erweiterungsfelder zurück. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} Objekt

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Ermittelt Schlüssel aus dem Wörterbuch.

**Returns:**
ICollection-Element

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Gibt den Namespace-URI nach Präfix zurück. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Gibt das Präfix nach Namespace-URI zurück. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ermittelt das Synchronisationsobjekt der Sammlung.

**Returns:**
Objektelement

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Ermittelt die Sammlung von Werten im Wörterbuch.

**Returns:**
ICollection Objekt

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Ruft die XmpMetadata der Eingabe‑PDF im XML-Format ab. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Die Bytes der XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Ruft die XmpMetadata der Eingabe‑PDF im XML-Format ab. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Die Bytes der XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Gibt true zurück, wenn die Sammlung eine feste Größe hat.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gibt true zurück, wenn die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gibt true zurück, wenn die Sammlung synchronisiert ist.

**Returns:**
boolescher Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Ermittelt das Enumerator‑Objekt des Wörterbuchs.

**Returns:**
Das Enumerator-Objekt.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Ermittelt das Enumerator‑Objekt der Sammlung.

**Returns:**
IEnumerator-Objekt

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Registriert den Namespace-URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das Schlüssel/Wert-Paar aus der Sammlung.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Entfernt das Element mit dem angegebenen Schlüssel. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel |  | Schlüssel des Elements, das gelöscht wird. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Entfernt den Schlüssel aus dem Wörterbuch. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Setzt den Wert nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Setzt den Wert der XMP-Metadaten nach Schlüssel. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Gibt die Anzahl der Elemente in der Sammlung zurück. </p>

**Returns:**
int-Wert <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird.
