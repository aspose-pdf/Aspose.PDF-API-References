---
title: DocumentInfo
second_title: Aspose.PDF for Java API Reference
description: Represents meta information of PDF document.
type: docs
weight: 97
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
| [getTitle()](#getTitle--) | Gets document title. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets document title. |
| [getCreator()](#getCreator--) | Gets document creator. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Sets document creator. |
| [getAuthor()](#getAuthor--) | Gets document author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets document author. |
| [getSubject()](#getSubject--) | Gets the subject of the document. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the document. |
| [getKeywords()](#getKeywords--) | Gets the keywords of the document. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Set the keywords of the document. |
| [getProducer()](#getProducer--) | Gets the document producer. |
| [setProducer(String value)](#setProducer-java.lang.String-) | Sets the document producer. |
| [getCreationDate()](#getCreationDate--) | Gets the date of document creation. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Sets the date of document creation. |
| [getCreationTimeZone()](#getCreationTimeZone--) | Time zone of creation date in milliseconds. |
| [setCreationTimeZone(double value)](#setCreationTimeZone-double-) | Time zone of creation date in milliseconds. |
| [getModTimeZone()](#getModTimeZone--) | Time zone of modification date. |
| [setModTimeZone(double value)](#setModTimeZone-double-) | Time zone of modification date. |
| [getModDate()](#getModDate--) | Gets the date of document modification. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Sets the date of document modification. |
| [getTrapped()](#getTrapped--) | Gets the trapped flag. |
| [setTrapped(String value)](#setTrapped-java.lang.String-) | Sets the trapped flag. |
| [clear()](#clear--) | Clears the document info. |
| [addItem(String key, String value)](#addItem-java.lang.String-java.lang.String-) | Adds an element with the specified key and value into the collection. |
| [remove(String key)](#remove-java.lang.String-) | Removes the element with the specified key from the collection. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets the value associated with the specified key. |
| [set_Item(String key, String value)](#set-Item-java.lang.String-java.lang.String-) | Sets the value associated with the specified key. |
| [clearCustomData()](#clearCustomData--) | Clears custom data only, leaves all other predefined values (Title, Author, etc.). |
| [isPredefinedKey(String key)](#isPredefinedKey-java.lang.String-) | Determines if the key is predefined (Title, Author, etc.), not custom. |
### DocumentInfo(IDocument document) {#DocumentInfo-com.aspose.pdf.IDocument-}
```
public DocumentInfo(IDocument document)
```


Initialize DocumentInfo instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The info of this document will be used for initialization. |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets document title.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCreator() {#getCreator--}
```
public String getCreator()
```


Gets document creator.

**Returns:**
java.lang.String - String value
### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Sets document creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets document author.

**Returns:**
java.lang.String - String value
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Sets document author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets the subject of the document.

**Returns:**
java.lang.String - String value
### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets the subject of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Gets the keywords of the document.

**Returns:**
java.lang.String - String value
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Set the keywords of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getProducer() {#getProducer--}
```
public String getProducer()
```


Gets the document producer.

**Returns:**
java.lang.String - String value
### setProducer(String value) {#setProducer-java.lang.String-}
```
public void setProducer(String value)
```


Sets the document producer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets the date of document creation.

**Returns:**
[Date](../../java.util/date) - Date object
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Sets the date of document creation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getCreationTimeZone() {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```


Time zone of creation date in milliseconds.

**Returns:**
double - double value
### setCreationTimeZone(double value) {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```


Time zone of creation date in milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | in milliseconds |

### getModTimeZone() {#getModTimeZone--}
```
public double getModTimeZone()
```


Time zone of modification date.

**Returns:**
double - double value
### setModTimeZone(double value) {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```


Time zone of modification date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getModDate() {#getModDate--}
```
public Date getModDate()
```


Gets the date of document modification.

**Returns:**
[Date](../../java.util/date) - Date object
### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Sets the date of document modification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getTrapped() {#getTrapped--}
```
public String getTrapped()
```


Gets the trapped flag.

**Returns:**
java.lang.String - String value
### setTrapped(String value) {#setTrapped-java.lang.String-}
```
public void setTrapped(String value)
```


Sets the trapped flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### clear() {#clear--}
```
public void clear()
```


Clears the document info.

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

### remove(String key) {#remove-java.lang.String-}
```
public void remove(String key)
```


Removes the element with the specified key from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of the element to remove. |

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

### clearCustomData() {#clearCustomData--}
```
public void clearCustomData()
```


Clears custom data only, leaves all other predefined values (Title, Author, etc.).

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
