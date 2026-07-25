---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 Pdf 格式的保存选项。"
type: docs
weight: 3790
url: /zh/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

导出为 Pdf 格式的保存选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | 默认用于计算机上缺失字体的字体名称。当保存为 PDF 的文档中包含在文档本身和设备上都不可用的字体时，API 会将这些字体替换为默认字体（如果设备上存在 {@code DefaultFontName} 对应的字体）。 |
| [getTempPath](#getTempPath--) | 临时文件的路径。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | 默认用于计算机上缺失字体的字体名称。当保存为 PDF 的文档中包含在文档本身和设备上都不可用的字体时，API 会将这些字体替换为默认字体（如果设备上存在 {@code DefaultFontName} 对应的字体）。 |
| [setTempPath](#setTempPath-java.lang.String-) | 临时文件的路径。 |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

构造函数

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

默认用于计算机上缺失字体的字体名称。当保存为 PDF 的文档中包含在文档本身和设备上都不可用的字体时，API 会将这些字体替换为默认字体（如果设备上存在 {@code DefaultFontName} 对应的字体）。

**Returns:**
字符串值

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

临时文件的路径。

**Returns:**
字符串值

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
默认用于计算机上缺失字体的字体名称。当保存为 PDF 的文档中包含在文档本身和设备上都不可用的字体时，API 会将这些字体替换为默认字体（如果设备上存在 {@code DefaultFontName} 对应的字体）。

### setTempPath {#setTempPath-java.lang.String-}
临时文件的路径。
