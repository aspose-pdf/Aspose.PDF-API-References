---
title: FontCollection
second_title: Aspose.PDF for Java API Reference
description: Represents font collection.
type: docs
weight: 132
url: /java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FontCollection implements Iterable<Font>
```

Represents font collection.

--------------------

```
The example demonstrates how to make all font declared on page as embedded.


 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // ensure all fonts declared on page resources are embedded
 // note that if fonts are declared on form resources they are not accessible from page resources
 for(com.aspsoe.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts())
 {
     if(!font.isEmbedded())
         font.isEmbedded(true);
 }
 doc.save("D:\\Tests\\input.pdf");
```

--------------------

Font collections represented by  FontCollection  class are used in several scenarios. For example, in resources with  Resources.Fonts  property.
## Methods

| Method | Description |
| --- | --- |
| [add(Font fragment)](#add-com.aspose.pdf.Font-) | Adds Font into collection. |
| [add(Font newFont, String[] resName)](#add-com.aspose.pdf.Font-java.lang.String---) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [add(String resName, IPdfObject newFont)](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Add new font to font collection. |
| [add(String resName, String baseFontName)](#add-java.lang.String-java.lang.String-) | Adds to font resources new font entry with specified base font name. |
| [clear_Rename_Namesake()](#clear-Rename-Namesake--) | Clears all items from the collection. |
| [contains(Font item)](#contains-com.aspose.pdf.Font-) | Determines whether the collection contains a specific value. |
| [contains(String name)](#contains-java.lang.String-) | Checks if font exists in font collection. |
| [copyTo(Font[] array, int index)](#copyTo-com.aspose.pdf.Font---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHash()](#getHash--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the font element at the specified index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets font from the collection by font name. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Font item)](#remove-com.aspose.pdf.Font-) | Deletes specified item from collection. |
| [size()](#size--) | Gets the number of  Font  object elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Font fragment) {#add-com.aspose.pdf.Font-}
```
public void add(Font fragment)
```


Adds Font into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragment | [Font](../../com.aspose.pdf/font) | Font object |

### add(Font newFont, String[] resName) {#add-com.aspose.pdf.Font-java.lang.String---}
```
public void add(Font newFont, String[] resName)
```


Adds new font to font resources and returns automatically assigned name of font resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFont | [Font](../../com.aspose.pdf/font) | Font object. |
| resName | java.lang.String[] | The automatically assigned resource item name. |

### add(String resName, IPdfObject newFont) {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
```
public void add(String resName, IPdfObject newFont)
```


Add new font to font collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resName | java.lang.String | String object |
| newFont | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | IPdfObject object |

### add(String resName, String baseFontName) {#add-java.lang.String-java.lang.String-}
```
public void add(String resName, String baseFontName)
```


Adds to font resources new font entry with specified base font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resName | java.lang.String | String object |
| baseFontName | java.lang.String | String object |

### clear_Rename_Namesake() {#clear-Rename-Namesake--}
```
public void clear_Rename_Namesake()
```


Clears all items from the collection.

### contains(Font item) {#contains-com.aspose.pdf.Font-}
```
public boolean contains(Font item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Checks if font exists in font collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Font name. |

**Returns:**
boolean - True in case collection contains the font with specified name.
### copyTo(Font[] array, int index) {#copyTo-com.aspose.pdf.Font---int-}
```
public void copyTo(Font[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Font\[\]](../../com.aspose.pdf/font) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHash() {#getHash--}
```
public HashDictionary<String,Font> getHash()
```




**Returns:**
[HashDictionary](../../com.aspose.pdf.engine.collections/hashdictionary)
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object for synchronization
### get_Item(int index) {#get-Item-int-}
```
public Font get_Item(int index)
```


Gets the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Font get_Item(String name)
```


Gets font from the collection by font name. Exception is thrown if font was not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the font. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Found font.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<Font> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.Font> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Font item) {#remove-com.aspose.pdf.Font-}
```
public boolean remove(Font item)
```


Deletes specified item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Font](../../com.aspose.pdf/font) | The object to delete |

**Returns:**
boolean - true if item was deleted from collection; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets the number of  Font  object elements actually contained in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

