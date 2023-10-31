---
title: ITeXInputDirectory
second_title: Aspose.PDF for Java API Reference
description: Interface of generalized TeX input directory.
type: docs
weight: 12
url: /java/com.aspose.pdf.tex/itexinputdirectory/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITeXInputDirectory extends Closeable
```

Interface of generalized TeX input directory.
## Methods

| Method | Description |
| --- | --- |
| [getFile(String fileName, String[] fullName)](#getFile-java.lang.String-java.lang.String---) | Returns the stream to read from or to write to. |
| [getFile(String fileName, String[] fullName, boolean searchSubdirectories)](#getFile-java.lang.String-java.lang.String---boolean-) | Returns the stream to read from or to write to. |
### getFile(String fileName, String[] fullName) {#getFile-java.lang.String-java.lang.String---}
```
public abstract InputStream getFile(String fileName, String[] fullName)
```


Returns the stream to read from or to write to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |

**Returns:**
java.io.InputStream - The stream.
### getFile(String fileName, String[] fullName, boolean searchSubdirectories) {#getFile-java.lang.String-java.lang.String---boolean-}
```
public abstract InputStream getFile(String fileName, String[] fullName, boolean searchSubdirectories)
```


Returns the stream to read from or to write to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |
| searchSubdirectories | boolean | Indicates whether to look for a file in subdirectories. |

**Returns:**
java.io.InputStream - The stream.
