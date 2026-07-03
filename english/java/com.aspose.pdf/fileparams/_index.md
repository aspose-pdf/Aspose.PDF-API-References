---
title: FileParams
second_title: Aspose.PDF for Java API Reference
description: Defines an embedded file parameter dictionary that shall contain additional file-specific information.
type: docs
weight: 1490
url: /java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Defines an embedded file parameter dictionary that shall contain additional file-specific information.

## Constructors

| Constructor | Description |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Constructor for FileParams class. |

## Methods

| Method | Description |
| --- | --- |
| [getCheckSum](#getCheckSum--) | A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream. |
| [getCreationDate](#getCreationDate--) | Get the date and time when the embedded file was created. |
| [getModDate](#getModDate--) | Get the date and time when the embedded file was last modified. |
| [getSize](#getSize--) | The size of the uncompressed embedded file, in bytes. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Set the date and time when the embedded file was created. |
| [setModDate](#setModDate-java.util.Date-) | Set the date and time when the embedded file was last modified. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Constructor for FileParams class.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream.

**Returns:**
String value

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Get the date and time when the embedded file was created.

**Returns:**
Date object

### getModDate {#getModDate--}
```
public Date getModDate()
```

Get the date and time when the embedded file was last modified.

**Returns:**
Date object

### getSize {#getSize--}
```
public int getSize()
```

The size of the uncompressed embedded file, in bytes.

**Returns:**
int value

### setCreationDate {#setCreationDate-java.util.Date-}
Set the date and time when the embedded file was created.

### setModDate {#setModDate-java.util.Date-}
Set the date and time when the embedded file was last modified.
