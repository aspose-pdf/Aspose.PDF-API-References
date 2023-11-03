---
title: ITeXOutputDirectory
second_title: Aspose.PDF for Java API Reference
description: Interface of generalized TeX output directory.
type: docs
weight: 13
url: /java/com.aspose.pdf.tex/itexoutputdirectory/
---
**All Implemented Interfaces:**
[com.aspose.pdf.tex.ITeXInputDirectory](../../com.aspose.pdf.tex/itexinputdirectory)
```
public interface ITeXOutputDirectory extends ITeXInputDirectory
```

Interface of generalized TeX output directory.
## Methods

| Method | Description |
| --- | --- |
| [getOutputFile(String fileName, String[] fullName)](#getOutputFile-java.lang.String-java.lang.String---) | Returns the stream to write to. |
### getOutputFile(String fileName, String[] fullName) {#getOutputFile-java.lang.String-java.lang.String---}
```
public abstract OutputStream getOutputFile(String fileName, String[] fullName)
```


Returns the stream to write to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The file name. |
| fullName | java.lang.String[] | The full file name. |

**Returns:**
java.io.OutputStream - The stream.
