---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示加载/导入 .mht 文件到 pdf 文档的选项。"
type: docs
weight: 4060
url: /zh/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

表示加载/导入 .mht 文件到 pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | 创建用于将 PostScript 转换为 pdf 文档的加载选项，基路径为空。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | 获取字体文件夹路径。用于转换的附加字体文件夹。 |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | 指定是否将非 TrueType 字体保存为 TTF。它显著降低 PS 转 PDF 转换后文档的体积，并提升包含大量非 TrueType 字体文本的 PS 文件转换为任何输出格式的速度。然而，在将 PostSctipt 文件转换为图像时会出现轻微的垂直文字位移。 |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | 指定是否将非 TrueType 字体保存为 TTF。它显著降低 PS 转 PDF 转换后文档的体积，并提升包含大量非 TrueType 字体文本的 PS 文件转换为任何输出格式的速度。然而，在将 PostSctipt 文件转换为图像时会出现轻微的垂直文字位移。 |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | 设置字体文件夹路径。用于转换的附加字体文件夹。 |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

创建用于将 PostScript 转换为 pdf 文档的加载选项，基路径为空。

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

获取字体文件夹路径。用于转换的附加字体文件夹。

**Returns:**
String 值数组

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

指定是否将非 TrueType 字体保存为 TTF。它显著降低 PS 转 PDF 转换后文档的体积，并提升包含大量非 TrueType 字体文本的 PS 文件转换为任何输出格式的速度。然而，在将 PostSctipt 文件转换为图像时会出现轻微的垂直文字位移。

**Returns:**
布尔值

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

指定是否将非 TrueType 字体保存为 TTF。它显著降低 PS 转 PDF 转换后文档的体积，并提升包含大量非 TrueType 字体文本的 PS 文件转换为任何输出格式的速度。然而，在将 PostSctipt 文件转换为图像时会出现轻微的垂直文字位移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
设置字体文件夹路径。用于转换的附加字体文件夹。
