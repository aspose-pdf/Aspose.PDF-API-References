---
title: FileParams
second_title: Aspose.PDF for Java API Reference
description: Defines an embedded file parameter dictionary that shall contain additional file-specific information.
type: docs
weight: 116
url: /java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object
```
public final class FileParams
```

Defines an embedded file parameter dictionary that shall contain additional file-specific information.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileParams(FileSpecification spec)](#FileParams-com.aspose.pdf.FileSpecification-) | Constructor for FileParams class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckSum()](#getCheckSum--) | A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | Get the date and time when the embedded file was created. |
| [getModDate()](#getModDate--) | Get the date and time when the embedded file was last modified. |
| [getSize()](#getSize--) | The size of the uncompressed embedded file, in bytes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Set the date and time when the embedded file was created. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Set the date and time when the embedded file was last modified. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileParams(FileSpecification spec) {#FileParams-com.aspose.pdf.FileSpecification-}
```
public FileParams(FileSpecification spec)
```


Constructor for FileParams class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| spec | [FileSpecification](../../com.aspose.pdf/filespecification) | File specification. |

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
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream.

**Returns:**
java.lang.String - String value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Get the date and time when the embedded file was created.

**Returns:**
[Date](../../java.util/date) - Date object
### getModDate() {#getModDate--}
```
public Date getModDate()
```


Get the date and time when the embedded file was last modified.

**Returns:**
[Date](../../java.util/date) - Date object
### getSize() {#getSize--}
```
public int getSize()
```


The size of the uncompressed embedded file, in bytes.

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




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Set the date and time when the embedded file was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Set the date and time when the embedded file was last modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

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

