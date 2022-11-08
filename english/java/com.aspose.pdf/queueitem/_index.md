---
title: PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for Java API Reference
description: Specifies encoding subtable.
type: docs
weight: 10
url: /java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object
```
public static class PdfASymbolicFontEncodingStrategy.QueueItem
```

Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificID). Enumeration  CMapEncodingTableType  and property  CMapEncodingTable  were implemented to make easier set of encoding subtable needed.
## Constructors

| Constructor | Description |
| --- | --- |
| [QueueItem()](#QueueItem--) | Constructor, specifies mac subtable(1,0) by default |
| [QueueItem(int platformID, int platformSpecificID)](#QueueItem-int-int-) | Constructor |
| [QueueItem(short cmapTable)](#QueueItem-short-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCMapEncodingTable()](#getCMapEncodingTable--) | Specifies encoding subtable via  CMapEncodingTableType enumeration |
| [getClass()](#getClass--) |  |
| [getPlatformId()](#getPlatformId--) | Platform identifier for encoding subtable |
| [getPlatformSpecificId()](#getPlatformSpecificId--) | Platform-specific encoding identifier for encoding subtable |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCMapEncodingTable(short value)](#setCMapEncodingTable-short-) | Specifies encoding subtable via  CMapEncodingTableType enumeration |
| [setPlatformId(int value)](#setPlatformId-int-) | Platform identifier for encoding subtable |
| [setPlatformSpecificId(int value)](#setPlatformSpecificId-int-) | Platform-specific encoding identifier for encoding subtable |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QueueItem() {#QueueItem--}
```
public QueueItem()
```


Constructor, specifies mac subtable(1,0) by default

### QueueItem(int platformID, int platformSpecificID) {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| platformID | int | Platform identifier for encoding subtable |
| platformSpecificID | int | Platform-specific encoding identifier for encoding subtable |

### QueueItem(short cmapTable) {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmapTable | short | encoding subtable |

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
### getCMapEncodingTable() {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```


Specifies encoding subtable via  CMapEncodingTableType enumeration

**Returns:**
short - encoding subtable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPlatformId() {#getPlatformId--}
```
public int getPlatformId()
```


Platform identifier for encoding subtable

**Returns:**
int - int value
### getPlatformSpecificId() {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```


Platform-specific encoding identifier for encoding subtable

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCMapEncodingTable(short value) {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```


Specifies encoding subtable via  CMapEncodingTableType enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | encoding subtable |

### setPlatformId(int value) {#setPlatformId-int-}
```
public void setPlatformId(int value)
```


Platform identifier for encoding subtable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPlatformSpecificId(int value) {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```


Platform-specific encoding identifier for encoding subtable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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

