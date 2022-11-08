---
title: DocumentInfo
second_title: Aspose.PDF for Java API Reference
description: Represents meta information of PDF document.
type: docs
weight: 94
url: /java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary
```
public final class DocumentInfo extends System.Collections.Generic.Dictionary<String,String>
```

Represents meta information of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentInfo(IDocument document)](#DocumentInfo-com.aspose.pdf.IDocument-) | Initialize DocumentInfo instance. |
## Methods

| Method | Description |
| --- | --- |
| [addItem(TKey arg0, TValue arg1)](#addItem-TKey-TValue-) |  |
| [addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [addItem(String key, String value)](#addItem-java.lang.String-java.lang.String-) | Adds an element with the specified key and value into the collection. |
| [clear()](#clear--) | Clears the document info. |
| [clearCustomData()](#clearCustomData--) | Clears custom data only, leaves all other predefined values (Title, Author, etc.). |
| [containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [containsKey(TKey arg0)](#containsKey-TKey-) |  |
| [containsValue(TValue arg0)](#containsValue-TValue-) |  |
| [copyTo(System.Array arg0, int arg1)](#copyTo-com.aspose.ms.System.Array-int-) |  |
| [copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthor()](#getAuthor--) | Gets document author. |
| [getClass()](#getClass--) |  |
| [getComparer()](#getComparer--) |  |
| [getCreationDate()](#getCreationDate--) | Gets the date of document creation. |
| [getCreationTimeZone()](#getCreationTimeZone--) | Time zone of creation date in milliseconds. |
| [getCreator()](#getCreator--) | Gets document creator. |
| [getDictionaryEntryEnumerator()](#getDictionaryEntryEnumerator--) |  |
| [getKeys()](#getKeys--) |  |
| [getKeywords()](#getKeywords--) | Gets the keywords of the document. |
| [getModDate()](#getModDate--) | Gets the date of document modification. |
| [getModTimeZone()](#getModTimeZone--) | Time zone of modification date. |
| [getProducer()](#getProducer--) | Gets the document producer. |
| [getSubject()](#getSubject--) | Gets the subject of the document. |
| [getSyncRoot()](#getSyncRoot--) |  |
| [getTitle()](#getTitle--) | Gets document title. |
| [getTrapped()](#getTrapped--) | Gets the trapped flag. |
| [getValues()](#getValues--) |  |
| [get_Item(TKey arg0)](#get-Item-TKey-) |  |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets the value associated with the specified key. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) |  |
| [isPredefinedKey(String key)](#isPredefinedKey-java.lang.String-) | Determines if the key is predefined (Title, Author, etc.), not custom. |
| [isReadOnly()](#isReadOnly--) |  |
| [isSynchronized()](#isSynchronized--) |  |
| [iterator()](#iterator--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Removes the element with the specified key from the collection. |
| [removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--) |  |
| [removeItemByKey(TKey arg0)](#removeItemByKey-TKey-) |  |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets document author. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Sets the date of document creation. |
| [setCreationTimeZone(double value)](#setCreationTimeZone-double-) | Time zone of creation date in milliseconds. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Sets document creator. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Set the keywords of the document. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Sets the date of document modification. |
| [setModTimeZone(double value)](#setModTimeZone-double-) | Time zone of modification date. |
| [setProducer(String value)](#setProducer-java.lang.String-) | Sets the document producer. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets document title. |
| [setTrapped(String value)](#setTrapped-java.lang.String-) | Sets the trapped flag. |
| [set_Item(TKey arg0, TValue arg1)](#set-Item-TKey-TValue-) |  |
| [set_Item(String key, String value)](#set-Item-java.lang.String-java.lang.String-) | Sets the value associated with the specified key. |
| [size()](#size--) |  |
| [toString()](#toString--) |  |
| [tryGetValue(TKey arg0, Object[] arg1)](#tryGetValue-TKey-java.lang.Object---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentInfo(IDocument document) {#DocumentInfo-com.aspose.pdf.IDocument-}
```
public DocumentInfo(IDocument document)
```


Initialize DocumentInfo instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The info of this document will be used for initialization. |

### addItem(TKey arg0, TValue arg1) {#addItem-TKey-TValue-}
```
public void addItem(TKey arg0, TValue arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

### addItem(String key, String value) {#addItem-java.lang.String-java.lang.String-}
```
public void addItem(String key, String value)
```


Adds an element with the specified key and value into the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of the element to add. |
| value | java.lang.String | The value of the element to add. The value can be null. |

### clear() {#clear--}
```
public void clear()
```


Clears the document info.

### clearCustomData() {#clearCustomData--}
```
public void clearCustomData()
```


Clears custom data only, leaves all other predefined values (Title, Author, etc.).

### containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**Returns:**
boolean
### containsKey(TKey arg0) {#containsKey-TKey-}
```
public boolean containsKey(TKey arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |

**Returns:**
boolean
### containsValue(TValue arg0) {#containsValue-TValue-}
```
public boolean containsValue(TValue arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TValue |  |

**Returns:**
boolean
### copyTo(System.Array arg0, int arg1) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Array |  |
| arg1 | int |  |

### copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<TKey,TValue>[] arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue>[] |  |
| arg1 | int |  |

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
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets document author.

**Returns:**
java.lang.String - String value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComparer() {#getComparer--}
```
public System.Collections.Generic.IGenericEqualityComparer<TKey> getComparer()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEqualityComparer<TKey>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets the date of document creation.

**Returns:**
[Date](../../java.util/date) - Date object
### getCreationTimeZone() {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```


Time zone of creation date in milliseconds.

**Returns:**
double - double value
### getCreator() {#getCreator--}
```
public String getCreator()
```


Gets document creator.

**Returns:**
java.lang.String - String value
### getDictionaryEntryEnumerator() {#getDictionaryEntryEnumerator--}
```
public System.Collections.IEnumerable<System.Collections.DictionaryEntry> getDictionaryEntryEnumerator()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.DictionaryEntry>
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue> getKeys()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<TKey,TValue>
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Gets the keywords of the document.

**Returns:**
java.lang.String - String value
### getModDate() {#getModDate--}
```
public Date getModDate()
```


Gets the date of document modification.

**Returns:**
[Date](../../java.util/date) - Date object
### getModTimeZone() {#getModTimeZone--}
```
public double getModTimeZone()
```


Time zone of modification date.

**Returns:**
double - double value
### getProducer() {#getProducer--}
```
public String getProducer()
```


Gets the document producer.

**Returns:**
java.lang.String - String value
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets the subject of the document.

**Returns:**
java.lang.String - String value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```




**Returns:**
java.lang.Object
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets document title.

**Returns:**
java.lang.String - String value
### getTrapped() {#getTrapped--}
```
public String getTrapped()
```


Gets the trapped flag.

**Returns:**
java.lang.String - String value
### getValues() {#getValues--}
```
public System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue> getValues()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.ValueCollection<TKey,TValue>
### get_Item(TKey arg0) {#get-Item-TKey-}
```
public TValue get_Item(TKey arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |

**Returns:**
TValue
### get_Item(String key) {#get-Item-java.lang.String-}
```
public String get_Item(String key)
```


Gets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key whose value to get or set. |

**Returns:**
java.lang.String - Value Object
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




**Returns:**
boolean
### isPredefinedKey(String key) {#isPredefinedKey-java.lang.String-}
```
public static boolean isPredefinedKey(String key)
```


Determines if the key is predefined (Title, Author, etc.), not custom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Selected key |

**Returns:**
boolean - True in case the key is predefined.
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.Generic.Dictionary.Enumerator<TKey,TValue> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.Enumerator<TKey,TValue>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public void remove(String key)
```


Removes the element with the specified key from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of the element to remove. |

### removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-TKey-TValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<TKey,TValue> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Collections.Generic.KeyValuePair<TKey,TValue> |  |

**Returns:**
boolean
### removeItemByKey(TKey arg0) {#removeItemByKey-TKey-}
```
public boolean removeItemByKey(TKey arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |

**Returns:**
boolean
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Sets document author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Sets the date of document creation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setCreationTimeZone(double value) {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```


Time zone of creation date in milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | in milliseconds |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Sets document creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Set the keywords of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Sets the date of document modification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setModTimeZone(double value) {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```


Time zone of modification date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setProducer(String value) {#setProducer-java.lang.String-}
```
public void setProducer(String value)
```


Sets the document producer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets the subject of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setTrapped(String value) {#setTrapped-java.lang.String-}
```
public void setTrapped(String value)
```


Sets the trapped flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### set_Item(TKey arg0, TValue arg1) {#set-Item-TKey-TValue-}
```
public void set_Item(TKey arg0, TValue arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | TValue |  |

### set_Item(String key, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String key, String value)
```


Sets the value associated with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | String Object |
| value | java.lang.String | Object |

### size() {#size--}
```
public int size()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(TKey arg0, Object[] arg1) {#tryGetValue-TKey-java.lang.Object---}
```
public boolean tryGetValue(TKey arg0, Object[] arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | TKey |  |
| arg1 | java.lang.Object[] |  |

**Returns:**
boolean
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

