---
title: TeXFileSystemOutputDirectory
second_title: Aspose.PDF for Java API Reference
description: Implements the regular file systems method for getting a file stream to write to.
type: docs
weight: 11
url: /java/com.aspose.pdf.tex/texfilesystemoutputdirectory/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tex.TeXFileSystemInputDirectory](../../com.aspose.pdf.tex/texfilesysteminputdirectory)

**All Implemented Interfaces:**
[com.aspose.pdf.tex.ITeXOutputDirectory](../../com.aspose.pdf.tex/itexoutputdirectory)
```
public class TeXFileSystemOutputDirectory extends TeXFileSystemInputDirectory implements ITeXOutputDirectory
```

Implements the regular file system's method for getting a file stream to write to.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXFileSystemOutputDirectory(String basePath)](#TeXFileSystemOutputDirectory-java.lang.String-) | Creates new instance. |
## Methods

| Method | Description |
| --- | --- |
| [getOutputFile(String fileName, String[] fullName)](#getOutputFile-java.lang.String-java.lang.String---) | Returns the stream to write to. |
### TeXFileSystemOutputDirectory(String basePath) {#TeXFileSystemOutputDirectory-java.lang.String-}
```
public TeXFileSystemOutputDirectory(String basePath)
```


Creates new instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| basePath | java.lang.String | The base path of the directory. |

### getOutputFile(String fileName, String[] fullName) {#getOutputFile-java.lang.String-java.lang.String---}
```
public final OutputStream getOutputFile(String fileName, String[] fullName)
```


Returns the stream to write to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |

**Returns:**
java.io.OutputStream - The stream.
