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
| [getSize()](#getSize--) | The size of the uncompressed embedded file, in bytes. |
| [getCreationDate()](#getCreationDate--) | Get the date and time when the embedded file was created. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Set the date and time when the embedded file was created. |
| [getModDate()](#getModDate--) | Get the date and time when the embedded file was last modified. |
| [setModDate(Date value)](#setModDate-java.util.Date-) | Set the date and time when the embedded file was last modified. |
| [getCheckSum()](#getCheckSum--) | A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. |
### FileParams(FileSpecification spec) {#FileParams-com.aspose.pdf.FileSpecification-}
```
public FileParams(FileSpecification spec)
```


Constructor for FileParams class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| spec | [FileSpecification](../../com.aspose.pdf/filespecification) | File specification. |

### getSize() {#getSize--}
```
public int getSize()
```


The size of the uncompressed embedded file, in bytes.

**Returns:**
int - int value
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Get the date and time when the embedded file was created.

**Returns:**
[Date](../../java.util/date) - Date object
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Set the date and time when the embedded file was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getModDate() {#getModDate--}
```
public Date getModDate()
```


Get the date and time when the embedded file was last modified.

**Returns:**
[Date](../../java.util/date) - Date object
### setModDate(Date value) {#setModDate-java.util.Date-}
```
public void setModDate(Date value)
```


Set the date and time when the embedded file was last modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream.

**Returns:**
java.lang.String - String value
