---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 TeX 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 4870
url: /zh/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

表示将 TeX 文件加载/导入到 PDF 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | 创建用于将 TeX 文件转换为 PDF 文档的默认加载选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDateTime](#getDateTime--) | 获取/设置日期/时间原语（如年份、月份、日期和时间）的特定值。 |
| [getInputDirectory](#getInputDirectory--) | 获取/设置 TeX 输入目录。 |
| [getJobName](#getJobName--) | 获取/设置作业的名称。 |
| [getLoadResult](#getLoadResult--) | 获取 TeX 加载和编译的结果——一切是否顺利，是否有任何评论/错误。 |
| [getNoLigatures](#getNoLigatures--) | 获取/设置取消所有字体连字的标志。 |
| [getOutputDirectory](#getOutputDirectory--) | 获取/设置 TeX 输出目录。 |
| [getRasterizeFormulas](#getRasterizeFormulas--) | 获取/设置允许光栅化数学公式的标志。 |
| [getRepeat](#getRepeat--) | 获取/设置指示是否需要在某些情况下（例如输入 TeX 文件中有引用）运行 TeX 作业两次的标志。一般来说，当引擎在排版过程中收集一些数据并在第一次运行时将其存储在辅助文件中时，此行为是有用的。第二次运行时，引擎会以某种方式使用这些数据。 |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | 获取/设置 TeX 所需的输入目录。所需的输入是以某种方式包含在主 .tex 文件中的文件，例如没有内置支持的包。 |
| [getShowTerminalOutput](#getShowTerminalOutput--) | 获取/设置指示是否在控制台显示终端输出的标志。 |
| [getSubsetFonts](#getSubsetFonts--) | 获取/设置指示是否在输出文件中子集化字体的标志。 |
| [setDateTime](#setDateTime-java.util.Date-) | 获取/设置日期/时间原语（如年份、月份、日期和时间）的特定值。 |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | 获取/设置 TeX 输入目录。 |
| [setJobName](#setJobName-java.lang.String-) | 获取/设置作业的名称。 |
| [setNoLigatures](#setNoLigatures-boolean-) | 获取/设置取消所有字体连字的标志。 |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | 获取/设置 TeX 输出目录。 |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | 获取/设置允许光栅化数学公式的标志。 |
| [setRepeat](#setRepeat-boolean-) | 获取/设置指示是否需要在某些情况下（例如输入 TeX 文件中有引用）运行 TeX 作业两次的标志。一般来说，当引擎在排版过程中收集一些数据并在第一次运行时将其存储在辅助文件中时，此行为是有用的。第二次运行时，引擎会以某种方式使用这些数据。 |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | 获取/设置 TeX 所需的输入目录。所需的输入是以某种方式包含在主 .tex 文件中的文件，例如没有内置支持的包。 |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | 获取/设置指示是否在控制台显示终端输出的标志。 |
| [setSubsetFonts](#setSubsetFonts-boolean-) | 获取/设置指示是否在输出文件中子集化字体的标志。 |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

创建用于将 TeX 文件转换为 PDF 文档的默认加载选项。

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

获取/设置日期/时间原语（如年份、月份、日期和时间）的特定值。

**Returns:**
Date 实例

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

获取/设置 TeX 输入目录。

**Returns:**
ITeXInputDirectory instance

### getJobName {#getJobName--}
```
public final String getJobName()
```

获取/设置作业的名称。

**Returns:**
字符串值

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

获取 TeX 加载和编译的结果——一切是否顺利，是否有任何评论/错误。

**Returns:**
TeXLoadResult element

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

获取/设置取消所有字体连字的标志。

**Returns:**
布尔值

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

获取/设置 TeX 输出目录。

**Returns:**
ITeXOutputDirectory instance

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

获取/设置允许光栅化数学公式的标志。

**Returns:**
布尔值

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

获取/设置指示是否需要在某些情况下（例如输入 TeX 文件中有引用）运行 TeX 作业两次的标志。一般来说，当引擎在排版过程中收集一些数据并在第一次运行时将其存储在辅助文件中时，此行为是有用的。第二次运行时，引擎会以某种方式使用这些数据。

**Returns:**
布尔值

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

获取/设置 TeX 所需的输入目录。所需的输入是以某种方式包含在主 .tex 文件中的文件，例如没有内置支持的包。

**Returns:**
ITeXInputDirectory instance

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

获取/设置指示是否在控制台显示终端输出的标志。

**Returns:**
布尔值

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

获取/设置指示是否在输出文件中子集化字体的标志。

**Returns:**
布尔值

### setDateTime {#setDateTime-java.util.Date-}
获取/设置日期/时间原语（如年份、月份、日期和时间）的特定值。

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
获取/设置 TeX 输入目录。

### setJobName {#setJobName-java.lang.String-}
获取/设置作业的名称。

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

获取/设置取消所有字体连字的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
获取/设置 TeX 输出目录。

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

获取/设置允许光栅化数学公式的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

获取/设置指示是否需要在某些情况下（例如输入 TeX 文件中有引用）运行 TeX 作业两次的标志。一般来说，当引擎在排版过程中收集一些数据并在第一次运行时将其存储在辅助文件中时，此行为是有用的。第二次运行时，引擎会以某种方式使用这些数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
获取/设置 TeX 所需的输入目录。所需的输入是以某种方式包含在主 .tex 文件中的文件，例如没有内置支持的包。

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

获取/设置指示是否在控制台显示终端输出的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

获取/设置指示是否在输出文件中子集化字体的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
