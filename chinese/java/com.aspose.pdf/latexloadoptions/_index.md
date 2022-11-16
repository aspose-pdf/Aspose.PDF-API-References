---
title: LatexLoadOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将 TeX 文件加载/导入 PDF 文档的选项。
type: docs
weight: 186
url: /zh/java/com.aspose.pdf/latexloadoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions), [com.aspose.pdf.TeXLoadOptions](../../com.aspose.pdf/texloadoptions)
```
public final class LatexLoadOptions extends TeXLoadOptions
```

表示将 TeX 文件加载/导入 PDF 文档的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LatexLoadOptions()](#LatexLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | 获取/设置日期/时间原语的特定值，例如\\年，\ \月，\ \天和\\时间。 |
| [getInputDirectory()](#getInputDirectory--) | 获取/设置 TeX 输入目录。 |
| [getJobName()](#getJobName--) | 获取/设置作业的名称。 |
| [getLoadFormat()](#getLoadFormat--) | 表示 LoadOptions 描述的文件格式。 |
| [getNoLigatures()](#getNoLigatures--) | 获取/设置取消所有字体中的连字的标志。 |
| [getOutputDirectory()](#getOutputDirectory--) | 获取/设置 TeX 输出目录。 |
| [getRasterizeFormulas()](#getRasterizeFormulas--) | 获取/设置允许栅格化数学公式的标志。 |
| [getRepeat()](#getRepeat--) | 获取/设置指示是否有必要运行 TeX 作业两次的标志，例如，在输入 TeX 文件中有引用。 |
| [getShowTerminalOutput()](#getShowTerminalOutput--) | 获取/设置指示是否在控制台上显示终端输出的标志。 |
| [getSubsetFonts()](#getSubsetFonts--) | 获取/设置指示是否对输出文件中的字体进行子集化的标志。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | 获取/设置日期/时间原语的特定值，例如\\年，\ \月，\ \天和\\时间。 |
| [setInputDirectory(ITeXInputDirectory value)](#setInputDirectory-com.aspose.tex.ITeXInputDirectory-) | 获取/设置 TeX 输入目录。 |
| [setJobName(String value)](#setJobName-java.lang.String-) | 获取/设置作业的名称。 |
| [setNoLigatures(boolean value)](#setNoLigatures-boolean-) | 获取/设置取消所有字体中的连字的标志。 |
| [setOutputDirectory(ITeXOutputDirectory value)](#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-) | 获取/设置 TeX 输出目录。 |
| [setRasterizeFormulas(boolean value)](#setRasterizeFormulas-boolean-) | 获取/设置允许栅格化数学公式的标志。 |
| [setRepeat(boolean value)](#setRepeat-boolean-) | 获取/设置指示是否有必要运行 TeX 作业两次的标志，例如，在输入 TeX 文件中有引用。 |
| [setShowTerminalOutput(boolean value)](#setShowTerminalOutput-boolean-) | 获取/设置指示是否在控制台上显示终端输出的标志。 |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | 获取/设置指示是否对输出文件中的字体进行子集化的标志。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LatexLoadOptions() {#LatexLoadOptions--}
```
public LatexLoadOptions()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


获取/设置日期/时间原语的特定值，例如\\年，\ \月，\ \天和\\时间。

**退货：**
[Date](../../java.util/date) - 日期实例
### getInputDirectory() {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```


获取/设置 TeX 输入目录。

**退货：**
com.aspose.tex.ITeXInputDirectory - ITeXInputDirectory 实例
### getJobName() {#getJobName--}
```
public final String getJobName()
```


获取/设置作业的名称。

**退货：**
java.lang.String - 字符串值
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


表示 LoadOptions 描述的文件格式。

**退货：**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat 元素
### getNoLigatures() {#getNoLigatures--}
```
public final boolean getNoLigatures()
```


获取/设置取消所有字体中的连字的标志。

**退货：**
boolean - 布尔值
### getOutputDirectory() {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```


获取/设置 TeX 输出目录。

**退货：**
com.aspose.tex.ITeXOutputDirectory - ITeXOutputDirectory 实例
### getRasterizeFormulas() {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```


获取/设置允许栅格化数学公式的标志。

**退货：**
boolean - 布尔值
### getRepeat() {#getRepeat--}
```
public final boolean getRepeat()
```


获取/设置指示是否有必要运行 TeX 作业两次的标志，例如，在输入 TeX 文件中有引用。通常，当引擎在排版过程中收集一些数据并将其存储在辅助文件中时，此行为很有用，所有这些都是在第一次运行时进行的。在第二次运行时，引擎会以某种方式使用该数据。

**退货：**
boolean - 布尔值
### getShowTerminalOutput() {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```


获取/设置指示是否在控制台上显示终端输出的标志。

**退货：**
boolean - 布尔值
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


获取/设置指示是否对输出文件中的字体进行子集化的标志。

**退货：**
boolean - 布尔值
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


获取/设置日期/时间原语的特定值，例如\\年，\ \月，\ \天和\\时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期实例 |

### setInputDirectory(ITeXInputDirectory value) {#setInputDirectory-com.aspose.tex.ITeXInputDirectory-}
```
public final void setInputDirectory(ITeXInputDirectory value)
```


获取/设置 TeX 输入目录。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.tex.ITeXInputDirectory | ITeXInputDirectory 实例 |

### setJobName(String value) {#setJobName-java.lang.String-}
```
public final void setJobName(String value)
```


获取/设置作业的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setNoLigatures(boolean value) {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```


获取/设置取消所有字体中的连字的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOutputDirectory(ITeXOutputDirectory value) {#setOutputDirectory-com.aspose.tex.ITeXOutputDirectory-}
```
public final void setOutputDirectory(ITeXOutputDirectory value)
```


获取/设置 TeX 输出目录。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.tex.ITeXOutputDirectory | ITeXOutputDirectory 实例 |

### setRasterizeFormulas(boolean value) {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```


获取/设置允许栅格化数学公式的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRepeat(boolean value) {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```


获取/设置指示是否有必要运行 TeX 作业两次的标志，例如，在输入 TeX 文件中有引用。通常，当引擎在排版过程中收集一些数据并将其存储在辅助文件中时，此行为很有用，所有这些都是在第一次运行时进行的。在第二次运行时，引擎会以某种方式使用该数据。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setShowTerminalOutput(boolean value) {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```


获取/设置指示是否在控制台上显示终端输出的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


获取/设置指示是否对输出文件中的字体进行子集化的标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Load 操作继续，但是用户也可以返回 Abort，在这种情况下 Load 操作应该停止。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback 值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
