---
title: PdfXmpMetadata
second_title: Aspose.PDF for Java API Reference
description: Class for manipulation with XMP metadata.
type: docs
weight: 620
url: /java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Class for manipulation with XMP metadata.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Constructor for PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Constructor for PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Adds extension field into metadata. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Adds value to XMP metadata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adds pair with key and value into the dictionary. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Adds new element to the dictionary object. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Adds new element to the dictionary object. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Removes all elements from the object. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Checks if dictionary contains the specified property. |
| [contains](#contains-java.lang.String-) | <p> Checks if dictionary contains the specified key. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copy metadata into array. |
| [get_Item](#get_Item-java.lang.String-) | <p> Gets value by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Gets value of XMP metadata by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Gets the dictionary of extension fields. </p> |
| [getKeys](#getKeys--) | Gets keys from the dictionary. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Gets namespace URI by prefix. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Gets the prefix by namespace URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Gets synchroniztion object of the collection. |
| [getValues](#getValues--) | Gets the collection of values in dictionary. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Get the XmpMetadata of the input pdf in a xml format. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Get the XmpMetadata of the input pdf in a xml format. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Returns true is collection has fixed size. |
| [isReadOnly](#isReadOnly--) | Returns true if collection is read-only. |
| [isSynchronized](#isSynchronized--) | Returns true if collection is synchronized. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Gets enumerator object of the dictionary. |
| [iteratorIt](#iteratorIt--) | Gets enumerator object of the collection. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Registers the namespace URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes key/value pair from the collection. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Removes element with specified key. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Removes key from the dictionary. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Sets value by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Sets value of XMP metadata by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Gets count if items in the collection. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tries to find key in the dictionary and retreives value if found. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Constructor for PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Constructor for PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Adds extension field into metadata.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Adds value to XMP metadata. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adds pair with key and value into the dictionary.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Adds new element to the dictionary object.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Adds new element to the dictionary object. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Removes all elements from the object. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Checks if dictionary contains the specified property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property |  | Property which will be checked. |

**Returns:**
True - if the dictionary contains the specified property; otherwise, false.

### contains {#contains-java.lang.String-}
<p> Checks if dictionary contains the specified key. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Checks does specified key-value pair is contained in the dictionary.

### containsKey {#containsKey-java.lang.String-}
Determines does this dictionary contasins specified key.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copy metadata into array.

### get_Item {#get_Item-java.lang.String-}
<p> Gets value by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Gets value of XMP metadata by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key |  | Key of the value. |

**Returns:**
Value from XMP metadata. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Gets the dictionary of extension fields. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} object

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Gets keys from the dictionary.

**Returns:**
ICollection element

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Gets namespace URI by prefix. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Gets the prefix by namespace URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets synchroniztion object of the collection.

**Returns:**
Object element

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Gets the collection of values in dictionary.

**Returns:**
ICollection object

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Get the XmpMetadata of the input pdf in a xml format. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
The bytes of the XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Get the XmpMetadata of the input pdf in a xml format. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
The bytes of the XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Returns true is collection has fixed size.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Returns true if collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true if collection is synchronized.

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Gets enumerator object of the dictionary.

**Returns:**
The enumerator object.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Gets enumerator object of the collection.

**Returns:**
IEnumerator object

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Registers the namespace URI. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes key/value pair from the collection.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Removes element with specified key. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key |  | Key of the element which will be deleted. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Removes key from the dictionary. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Sets value by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Sets value of XMP metadata by key. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Gets count if items in the collection. </p>

**Returns:**
int value <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tries to find key in the dictionary and retreives value if found.
