---
title: DocumentInfo
second_title: Aspose.PDF for Java API Reference
description: Represents meta information of PDF document.
type: docs
weight: 1160
url: /java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Represents meta information of PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Initialize DocumentInfo instance. |

## Methods

| Method | Description |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Adds an element with the specified key and value into the collection. |
| [clear](#clear--) | Clears the document info. |
| [clearCustomData](#clearCustomData--) | Clears custom data only, leaves all other predefined values (Title, Author, etc.). |
| [get_Item](#get_Item-java.lang.String-) | Gets the value associated with the specified key. |
| [getAuthor](#getAuthor--) | Gets document author. |
| [getCreationDate](#getCreationDate--) | Gets the date of document creation. |
| [getCreationTimeZone](#getCreationTimeZone--) | Time zone of creation date in milliseconds. |
| [getCreator](#getCreator--) | Gets document creator. |
| [getKeywords](#getKeywords--) | Gets the keywords of the document. |
| [getModDate](#getModDate--) | Gets the date of document modification. |
| [getModTimeZone](#getModTimeZone--) | Time zone of modification date. |
| [getProducer](#getProducer--) | Gets the document producer. |
| [getSubject](#getSubject--) | Gets the subject of the document. |
| [getTitle](#getTitle--) | Gets document title. |
| [getTrapped](#getTrapped--) | Gets the trapped flag. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Determines if the key is predefined (Title, Author, etc.), not custom. |
| [remove](#remove-java.lang.String-) | Removes the element with the specified key from the collection. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Sets the value associated with the specified key. |
| [setAuthor](#setAuthor-java.lang.String-) | Sets document author. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Sets the date of document creation. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Time zone of creation date in milliseconds. |
| [setCreator](#setCreator-java.lang.String-) | Sets document creator. |
| [setKeywords](#setKeywords-java.lang.String-) | Set the keywords of the document. |
| [setModDate](#setModDate-java.util.Date-) | Sets the date of document modification. |
| [setModTimeZone](#setModTimeZone-double-) | Time zone of modification date. |
| [setProducer](#setProducer-java.lang.String-) | Sets the document producer. |
| [setSubject](#setSubject-java.lang.String-) | Sets the subject of the document. |
| [setTitle](#setTitle-java.lang.String-) | Sets document title. |
| [setTrapped](#setTrapped-java.lang.String-) | Sets the trapped flag. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Initialize DocumentInfo instance.

### addItem {#addItem-java.lang.String-java.lang.String-}
Adds an element with the specified key and value into the collection.

### clear {#clear--}
```
public void clear()
```

Clears the document info.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Clears custom data only, leaves all other predefined values (Title, Author, etc.).

### get_Item {#get_Item-java.lang.String-}
Gets the value associated with the specified key.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Gets document author.

**Returns:**
String value

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Gets the date of document creation.

**Returns:**
Date object

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Time zone of creation date in milliseconds.

**Returns:**
double value

### getCreator {#getCreator--}
```
public String getCreator()
```

Gets document creator.

**Returns:**
String value

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Gets the keywords of the document.

**Returns:**
String value

### getModDate {#getModDate--}
```
public Date getModDate()
```

Gets the date of document modification.

**Returns:**
Date object

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Time zone of modification date.

**Returns:**
double value

### getProducer {#getProducer--}
```
public String getProducer()
```

Gets the document producer.

**Returns:**
String value

### getSubject {#getSubject--}
```
public String getSubject()
```

Gets the subject of the document.

**Returns:**
String value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets document title.

**Returns:**
String value

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Gets the trapped flag.

**Returns:**
String value

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Determines if the key is predefined (Title, Author, etc.), not custom.

### remove {#remove-java.lang.String-}
Removes the element with the specified key from the collection.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Sets the value associated with the specified key.

### setAuthor {#setAuthor-java.lang.String-}
Sets document author.

### setCreationDate {#setCreationDate-java.util.Date-}
Sets the date of document creation.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Time zone of creation date in milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | in milliseconds |

### setCreator {#setCreator-java.lang.String-}
Sets document creator.

### setKeywords {#setKeywords-java.lang.String-}
Set the keywords of the document.

### setModDate {#setModDate-java.util.Date-}
Sets the date of document modification.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Time zone of modification date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setProducer {#setProducer-java.lang.String-}
Sets the document producer.

### setSubject {#setSubject-java.lang.String-}
Sets the subject of the document.

### setTitle {#setTitle-java.lang.String-}
Sets document title.

### setTrapped {#setTrapped-java.lang.String-}
Sets the trapped flag.
