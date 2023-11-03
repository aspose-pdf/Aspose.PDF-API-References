---
title: TeXFileSystemInputDirectory
second_title: Aspose.PDF for Java API Reference
description: Implements the regular file systems method for getting a file stream to read from.
type: docs
weight: 10
url: /java/com.aspose.pdf.tex/texfilesysteminputdirectory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.tex.ITeXInputDirectory](../../com.aspose.pdf.tex/itexinputdirectory)
```
public class TeXFileSystemInputDirectory implements ITeXInputDirectory
```

Implements the regular file system's method for getting a file stream to read from.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXFileSystemInputDirectory(String basePath)](#TeXFileSystemInputDirectory-java.lang.String-) | Creates new instance. |
## Methods

| Method | Description |
| --- | --- |
| [getFile(String fileName, String[] fullName)](#getFile-java.lang.String-java.lang.String---) | Returns the stream to read from. |
| [getFile(String fileName, String[] fullName, boolean searchSubdirectories)](#getFile-java.lang.String-java.lang.String---boolean-) | Returns the stream to read from. |
| [close()](#close--) | Disposes the instance. |
| [dispose()](#dispose--) | Disposes the instance. |
### TeXFileSystemInputDirectory(String basePath) {#TeXFileSystemInputDirectory-java.lang.String-}
```
public TeXFileSystemInputDirectory(String basePath)
```


Creates new instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basePath | java.lang.String | The base path of the directory. |

### getFile(String fileName, String[] fullName) {#getFile-java.lang.String-java.lang.String---}
```
public final InputStream getFile(String fileName, String[] fullName)
```


Returns the stream to read from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |

**Returns:**
java.io.InputStream - The stream.
### getFile(String fileName, String[] fullName, boolean searchSubdirectories) {#getFile-java.lang.String-java.lang.String---boolean-}
```
public final InputStream getFile(String fileName, String[] fullName, boolean searchSubdirectories)
```


Returns the stream to read from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |
| searchSubdirectories | boolean | Indicates whether to look for a file in subdirectories. |

**Returns:**
java.io.InputStream - The stream.
### close() {#close--}
```
public void close()
```


Disposes the instance.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the instance.

