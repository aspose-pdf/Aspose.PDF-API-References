---
title: PdfXmpMetadata
second_title: Aspose.PDF for Java API Reference
description: Class for manipulation with XMP metadata.
type: docs
weight: 54
url: /java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class PdfXmpMetadata extends SaveableFacade implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

Class for manipulation with XMP metadata.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfXmpMetadata()](#PdfXmpMetadata--) | Constructor for PdfXmpMetadata. |
| [PdfXmpMetadata(IDocument document)](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | Initializes new  PdfXmpMetadata  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Adds extension field into metadata. |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Adds pair with key and value into the dictionary. |
| [addItem(int key, XmpValue value)](#addItem-int-com.aspose.pdf.XmpValue-) | Adds value to XMP metadata. |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Adds new element to the dictionary object. |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | Adds new element to the dictionary object. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [clear()](#clear--) | Removes all elements from the object. |
| [close()](#close--) | Disposes Document bound with a facade. |
| [contains(int property)](#contains-int-) | Checks if dictionary contains the specified property. |
| [contains(String key)](#contains-java.lang.String-) | Checks if dictionary contains the specified key. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | Copy metadata into array. |
| [dispose()](#dispose--) | Disposes the facade. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getByDefaultMetadataProperties(int key)](#getByDefaultMetadataProperties-int-) | Gets value of XMP metadata by key. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getExtensionFields()](#getExtensionFields--) | Gets the dictionary of extension fields. |
| [getKeys()](#getKeys--) | Gets keys from the dictionary. |
| [getNamespaceURIByPrefix(String prefix)](#getNamespaceURIByPrefix-java.lang.String-) | Gets namespace URI by prefix. |
| [getPrefixByNamespaceURI(String namespaceURI)](#getPrefixByNamespaceURI-java.lang.String-) | Gets the prefix by namespace URI. |
| [getSyncRoot()](#getSyncRoot--) | Gets synchroniztion object of the collection. |
| [getValues()](#getValues--) | Gets the collection of values in dictionary. |
| [getXmpMetadata()](#getXmpMetadata--) | Get the XmpMetadata of the input pdf in a xml format. |
| [getXmpMetadata(String name)](#getXmpMetadata-java.lang.String-) | Get a part of the XmpMetadata of the input pdf according to a meta name. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets value by key. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Returns true is collection has fixed size. |
| [isReadOnly()](#isReadOnly--) | Returns true if collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Returns true if collection is synchronized. |
| [iterator()](#iterator--) | Gets enumerator object of the dictionary. |
| [iteratorIt()](#iteratorIt--) | Gets enumerator object of the collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceURI(String prefix, String namespaceURI)](#registerNamespaceURI-java.lang.String-java.lang.String-) | Registers the namespace URI. |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Removes key/value pair from the collection. |
| [removeItemByKey(int key)](#removeItemByKey-int-) | Removes element with specified key. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Removes key from the dictionary. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the PDF document to the specified stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves the PDF document to the specified file. |
| [setByDefaultMetadataProperties(int key, XmpValue value)](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | Sets value of XMP metadata by key. |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | Sets value by key. |
| [size()](#size--) | Gets count if items in the collection. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Tries to find key in the dictionary and retreives value if found. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfXmpMetadata() {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```


Constructor for PdfXmpMetadata.

--------------------

```
PdfXmlMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
```

### PdfXmpMetadata(IDocument document) {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
```
public PdfXmpMetadata(IDocument document)
```


Initializes new  PdfXmpMetadata  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription) {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
```
public void add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)
```


Adds extension field into metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | The pdf extension object to add. |
| namespacePrefix | java.lang.String | The prefix of schema. |
| namespaceUri | java.lang.String | The namespace uri of schema. |
| schemaDescription | java.lang.String | The optional description of schema. |

### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Adds pair with key and value into the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Item to be added. |

### addItem(int key, XmpValue value) {#addItem-int-com.aspose.pdf.XmpValue-}
```
public void addItem(int key, XmpValue value)
```


Adds value to XMP metadata.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add(DefaultMetadataProperties.Nickname, "name1");
 xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key name. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Value which will be added. |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


Adds new element to the dictionary object.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of new element. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Value of the element. |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


Adds new element to the dictionary object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of new element. |
| value | java.lang.Object | Value of the element. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### clear() {#clear--}
```
public void clear()
```


Removes all elements from the object.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.clear();
```

### close() {#close--}
```
public void close()
```


Disposes Document bound with a facade.

### contains(int property) {#contains-int-}
```
public boolean contains(int property)
```


Checks if dictionary contains the specified property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | int | Property which will be checked. |

**Returns:**
boolean - True - if the dictionary contains the specified property; otherwise, false.
### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


Checks if dictionary contains the specified key.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
 if (!xmp.contains("xmp:Nickname"))
   System.out.println("Key does not exists");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key which will be checked. |

**Returns:**
boolean - True - if the dictionary contains the specified key; otherwise, false.
### containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Checks does specified key-value pair is contained in the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Key-value pair. |

**Returns:**
boolean - true if this pauir was found.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determines does this dictionary contasins specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to search in the dictionary. |

**Returns:**
boolean - true if key is found.
### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


Copy metadata into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | The destination array. |
| index | int | The starting index. |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getByDefaultMetadataProperties(int key) {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```


Gets value of XMP metadata by key.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | Key of the value. |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Value from XMP metadata.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


Gets the dictionary of extension fields.

**Returns:**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> -  Hashtable  object
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Gets keys from the dictionary.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - ICollection element
### getNamespaceURIByPrefix(String prefix) {#getNamespaceURIByPrefix-java.lang.String-}
```
public String getNamespaceURIByPrefix(String prefix)
```


Gets namespace URI by prefix.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getNamespaceURIByPrefix("xmp"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |

**Returns:**
java.lang.String - Namespace URI.
### getPrefixByNamespaceURI(String namespaceURI) {#getPrefixByNamespaceURI-java.lang.String-}
```
public String getPrefixByNamespaceURI(String namespaceURI)
```


Gets the prefix by namespace URI.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | java.lang.String | Namespace URI. |

**Returns:**
java.lang.String - The prefix value.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchroniztion object of the collection.

**Returns:**
java.lang.Object - Object element
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


Gets the collection of values in dictionary.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> - ICollection object
### getXmpMetadata() {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```


Get the XmpMetadata of the input pdf in a xml format.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata();
```

**Returns:**
byte[] - The bytes of the XmpMetadata.
### getXmpMetadata(String name) {#getXmpMetadata-java.lang.String-}
```
public byte[] getXmpMetadata(String name)
```


Get a part of the XmpMetadata of the input pdf according to a meta name.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata("dc:creator");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Metadata name. |

**Returns:**
byte[] - Bytes of metadata.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


Gets value by key.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key name to get. |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Object by key
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```


Returns true is collection has fixed size.

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Returns true if collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if collection is synchronized.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


Gets enumerator object of the dictionary.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - The enumerator object.
### iteratorIt() {#iteratorIt--}
```
public System.Collections.IEnumerator iteratorIt()
```


Gets enumerator object of the collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - IEnumerator object
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceURI(String prefix, String namespaceURI) {#registerNamespaceURI-java.lang.String-java.lang.String-}
```
public void registerNamespaceURI(String prefix, String namespaceURI)
```


Registers the namespace URI.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceURI | java.lang.String | The namespace URI. |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Removes key/value pair from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Key/value pair to be removed. |

**Returns:**
boolean - true if pair was found and removed.
### removeItemByKey(int key) {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```


Removes element with specified key.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove(DefaultMetadataProperties.Nickname);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | Key of the element which will be deleted. |

### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Removes key from the dictionary.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove("xmp:Nickname");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key which will be removed. |

**Returns:**
boolean - True - if key removed; otherwise, false.
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves the PDF document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | The destination stream. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | The destination file. |

### setByDefaultMetadataProperties(int key, XmpValue value) {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
```
public void setByDefaultMetadataProperties(int key, XmpValue value)
```


Sets value of XMP metadata by key.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | Key of the DefaultMetadataProperties value. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Object. |

### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


Sets value by key.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key name to set. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | The value to set. |

### size() {#size--}
```
public int size()
```


Gets count if items in the collection.

**Returns:**
int - int value

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println("Count = " + pxm.size());
```
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public boolean tryGetValue(String key, Object[] value)
```


Tries to find key in the dictionary and retreives value if found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to search in the dictionary. |
| value | java.lang.Object[] | Retreived value. |

**Returns:**
boolean - true if key was found.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

