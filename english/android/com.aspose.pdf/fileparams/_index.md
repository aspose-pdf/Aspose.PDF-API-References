---
title: FileParams
second_title: Aspose.PDF for Java API Reference
description: Defines an embedded file parameter dictionary that shall contain additional file-specific information.
type: docs
weight: 99
url: /java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object
```
public final class FileParams
```

Defines an embedded file parameter dictionary that shall contain additional file-specific information.
## Methods

| Method | Description |
| --- | --- |
| [getEngineDict()](#getEngineDict--) |  |
| [getSize()](#getSize--) | The size of the uncompressed embedded file, in bytes. |
| [getCreationDate()](#getCreationDate--) |  |
| [getModDate()](#getModDate--) |  |
| [getCheckSum()](#getCheckSum--) | A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. |
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getSize() {#getSize--}
```
public int getSize()
```


The size of the uncompressed embedded file, in bytes.

**Returns:**
int
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```




**Returns:**
[Date](../../java.util/date)
### getModDate() {#getModDate--}
```
public Date getModDate()
```




**Returns:**
[Date](../../java.util/date)
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream.

**Returns:**
java.lang.String
