---
title: PdfFormatConversionOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示转换 PDF 文档的选项集
type: docs
weight: 278
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions/
---
**遗产：**
java.lang.Object
```
public class PdfFormatConversionOptions
```

表示转换 PDF 文档的选项集
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-) | 构造函数 |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | 构造函数 |
| [PdfFormatConversionOptions(PdfFormat format)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | 构造函数 |
| [PdfFormatConversionOptions(PdfFormat format, int action)](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-) | 构造函数 |
| [PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-) | 构造函数 |
| [PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addNotAccessibleFont(String fontName)](#addNotAccessibleFont-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignStrategy()](#getAlignStrategy--) | 对齐文本的策略。 |
| [getAlignText()](#getAlignText--) | 此标志控制转换文档中的文本对齐方式。 |
| [getClass()](#getClass--) |  |
| [getConvertSoftMaskAction()](#getConvertSoftMaskAction--) | 带有软蒙版的图像的动作。 |
| [getDefault()](#getDefault--) | 使用默认参数获取 PdfFormatConversionOptions 对象 |
| [getErrorAction()](#getErrorAction--) | 无法转换的对象的操作 |
| [getExcludeFontsStrategy()](#getExcludeFontsStrategy--) | 排除多余字体并减小文档文件大小的策略。 |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) | 无法将某些字体嵌入 PDF 文档的情况下的选项。 |
| [getFormat()](#getFormat--) | PDF 格式。 |
| [getIccProfileFileName()](#getIccProfileFileName--) | 获取 icc 配置文件名称的文件名。 |
| [getLogFileName()](#getLogFileName--) | 将存储评论的文件路径。 |
| [getLogStream()](#getLogStream--) | 将存储评论的流。 |
| [getNonSpecificationCases()](#getNonSpecificationCases--) | 当源文档不符合 PDF/A 规范时，保留标志以控制 PDF/A 转换过程。 |
| [getNotAccessibleFonts()](#getNotAccessibleFonts--) | 此属性是财产外。 |
| [getOptimizeFileSize()](#getOptimizeFileSize--) | 获取启用/禁用特殊转换模式的标志，以获取文件大小减小的 PDF/A 文档。 |
| [getPuaTextProcessingStrategy()](#getPuaTextProcessingStrategy--) | 处理来自 unicode 专用区 (PUA) 的符号的策略。 |
| [getSymbolicFontEncodingStrategy()](#getSymbolicFontEncodingStrategy--) | 如果符号 TrueType 字体具有多个编码子表，则复制符号字体编码数据的策略。 |
| [getTransparencyAction()](#getTransparencyAction--) | 图像蒙版对象的操作 |
| [getTransparencyResolution()](#getTransparencyResolution--) | 在转换透明图像期间设置分辨率。 |
| [getUnicodeProcessingRules()](#getUnicodeProcessingRules--) | 解决 unicode 映射问题的规则。 |
| [hashCode()](#hashCode--) |  |
| [isAsyncImageStreamsConversionMode()](#isAsyncImageStreamsConversionMode--) | 获取/设置异步模式下图像流的运行。 |
| [isLowMemoryMode()](#isLowMemoryMode--) | 是否启用低内存转换模式 |
| [isPageByPageFontProcess()](#isPageByPageFontProcess--) | 是否启用了逐页基础模式的字体分析 |
| [isTransferInfo()](#isTransferInfo--) | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。 |
| [isTransparencyIgnore()](#isTransparencyIgnore--) | 默认值 FALSE 和透明颜色将继续保持文档外观。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignStrategy(byte alignStrategy)](#setAlignStrategy-byte-) | 对齐文本的策略。 |
| [setAlignText(boolean value)](#setAlignText-boolean-) | 此标志控制转换文档中的文本对齐方式。 |
| [setAsyncImageStreamsConversionMode(boolean value)](#setAsyncImageStreamsConversionMode-boolean-) | 获取/设置异步模式下图像流的运行。 |
| [setConvertSoftMaskAction(int value)](#setConvertSoftMaskAction-int-) | 带有软蒙版的图像的动作。 |
| [setErrorAction(int value)](#setErrorAction-int-) | 无法转换的对象的操作 |
| [setExcludeFontsStrategy(byte value)](#setExcludeFontsStrategy-byte-) | 排除多余字体并减小文档文件大小的策略。 |
| [setFormat(PdfFormat value)](#setFormat-com.aspose.pdf.PdfFormat-) | PDF 格式。 |
| [setIccProfileFileName(String value)](#setIccProfileFileName-java.lang.String-) | 设置 icc 配置文件名称的文件名。 |
| [setLogFileName(String value)](#setLogFileName-java.lang.String-) | 将存储评论的文件路径。 |
| [setLogStream(OutputStream value)](#setLogStream-java.io.OutputStream-) | 将存储评论的流。 |
| [setLowMemoryMode(boolean value)](#setLowMemoryMode-boolean-) | 是否启用低内存转换模式 |
| [setOptimizeFileSize(boolean value)](#setOptimizeFileSize-boolean-) | 设置一个启用/禁用特殊转换模式的标志，以获取文件大小减小的 PDF/A 文档。 |
| [setPageByPageFontProcess(boolean b)](#setPageByPageFontProcess-boolean-) | 启用逐页基础模式设置页面字体分析 |
| [setPuaTextProcessingStrategy(int value)](#setPuaTextProcessingStrategy-int-) | 处理来自 unicode 专用区 (PUA) 的符号的策略。 |
| [setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | 如果符号 TrueType 字体具有多个编码子表，则复制符号字体编码数据的策略。 |
| [setTransferInfo(boolean value)](#setTransferInfo-boolean-) | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。 |
| [setTransparencyAction(int value)](#setTransparencyAction-int-) | 图像蒙版对象的操作 |
| [setTransparencyIgnore(boolean value)](#setTransparencyIgnore-boolean-) | 默认值 FALSE 和透明颜色将继续保持文档外观。 |
| [setTransparencyResolution(int dpi)](#setTransparencyResolution-int-) | 在转换透明图像期间设置分辨率。 |
| [setUnicodeProcessingRules(ToUnicodeProcessingRules value)](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | 解决 unicode 映射问题的规则。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |
| action | int | 无法转换的对象的操作 |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |

### PdfFormatConversionOptions(PdfFormat format) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
```
public PdfFormatConversionOptions(PdfFormat format)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |

### PdfFormatConversionOptions(PdfFormat format, int action) {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(PdfFormat format, int action)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |
| action | int | 无法转换的对象的操作 |

### PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction) {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-int-int-}
```
public PdfFormatConversionOptions(String outputLogFileName, PdfFormat format, int action, int transparencyAction)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogFileName | java.lang.String | 将存储评论的文件路径。 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf 格式。 |
| action | int | 无法转换的对象的操作 |
| transparencyAction | int | 图像蒙版对象的操作 |

### PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action) {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-int-}
```
public PdfFormatConversionOptions(OutputStream outputLogStream, PdfFormat format, int action)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputLogStream | java.io.OutputStream | 将存储评论的流 |
| format | [PdfFormat](../../com.aspose.pdf/pdfformat) | pdf格式 |
| action | int | 无法转换的对象的操作 |

### addNotAccessibleFont(String fontName) {#addNotAccessibleFont-java.lang.String-}
```
public void addNotAccessibleFont(String fontName)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String |  |

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
### getAlignStrategy() {#getAlignStrategy--}
```
public byte getAlignStrategy()
```


对齐文本的策略。仅当标志 AlignText 设置为 true 时，此参数才有意义。

**退货：**
byte - SegmentAlignStrategy 元素
### getAlignText() {#getAlignText--}
```
public boolean getAlignText()
```


此标志控制转换文档中的文本对齐方式。默认情况下，文档转换不会影响文本对齐并保持文本原样。但在某些情况下，字体替换会导致转换后的文档中出现文本重叠或额外空格。设置此标志后，将执行特殊对齐操作。此标志应仅针对存在重叠文本或额外文本空间问题的文档设置，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getConvertSoftMaskAction() {#getConvertSoftMaskAction--}
```
public final int getConvertSoftMaskAction()
```


带有软蒙版的图像的动作。

**退货：**
int - 整数值
### getDefault() {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```


使用默认参数获取 PdfFormatConversionOptions 对象

**退货：**
[PdfFormatConversionOptions](../../com.aspose.pdf/pdfformatconversionoptions) PdfFormatConversionOptions 对象
### getErrorAction() {#getErrorAction--}
```
public int getErrorAction()
```


无法转换的对象的操作

**退货：**
int - ConvertErrorAction 元素
### getExcludeFontsStrategy() {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```


排除多余字体并减小文档文件大小的策略。只有当标志 OptimizeFileSize 设置为 true 时，此参数才有意义。默认情况下，使用 SubsetFonts 和 RemoveDuplicatedFonts 策略组合。

**退货：**
字节 - 字节值
### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```


无法将某些字体嵌入 PDF 文档的情况下的选项。

**退货：**
[FontEmbeddingOptions](../../com.aspose.pdf/fontembeddingoptions) FontEmbeddingOptions 对象
### getFormat() {#getFormat--}
```
public PdfFormat getFormat()
```


PDF 格式。

**退货：**
[PdfFormat](../../com.aspose.pdf/pdfformat) - PdfFormat 元素
### getIccProfileFileName() {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```


获取 icc 配置文件名称的文件名。如果为 null，则使用默认的 icc 配置文件。

**退货：**
java.lang.String - 字符串对象
### getLogFileName() {#getLogFileName--}
```
public String getLogFileName()
```


将存储评论的文件路径。

**退货：**
java.lang.String - 字符串对象
### getLogStream() {#getLogStream--}
```
public OutputStream getLogStream()
```


将存储评论的流。

**退货：**
java.io.OutputStream - OutputStream 对象
### getNonSpecificationCases() {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```


当源文档不符合 PDF/A 规范时，保留标志以控制 PDF/A 转换过程。

**退货：**
[PdfANonSpecificationFlags](../../com.aspose.pdf/pdfanonspecificationflags) PdfANonSpecificationFlags 对象
### getNotAccessibleFonts() {#getNotAccessibleFonts--}
```
public String[] getNotAccessibleFonts()
```


此属性是财产外。它保存了上次 PDF/A 转换时在计算机上找不到的所有字体（字体名称）。

**退货：**
java.lang.字符串[] - 字符串数组
### getOptimizeFileSize() {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```


获取启用/禁用特殊转换模式的标志，以获取文件大小减小的 PDF/A 文档。

现在这个标志影响了PDF文档中使用的字体的优化，可能在未来，这个标志也会被用来打开其他数据结构的优化，比如图形。

设置此标志和模式可以显着减小文件大小，但同时会显着降低转换性能。

**退货：**
boolean - 布尔值
### getPuaTextProcessingStrategy() {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```


处理来自 unicode 专用区 (PUA) 的符号的策略。

**退货：**
int - PuaProcessingStrategy 元素
### getSymbolicFontEncodingStrategy() {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```


如果符号 TrueType 字体具有多个编码子表，则复制符号字体编码数据的策略。

**退货：**
[PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) PdfASymbolicFontEncodingStrategy 对象
### getTransparencyAction() {#getTransparencyAction--}
```
public int getTransparencyAction()
```


图像蒙版对象的操作

**退货：**
int - ConvertTransparencyAction 元素
### getTransparencyResolution() {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```


在转换透明图像期间设置分辨率。分辨率越高，转换速度越慢。默认值为 300。

**退货：**
int - 分辨率值
### getUnicodeProcessingRules() {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```


解决 unicode 映射问题的规则。可以为空。

**退货：**
[ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) - ToUnicodeProcessingRules 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isAsyncImageStreamsConversionMode() {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```


获取/设置异步模式下图像流的运行。

**退货：**
boolean - 布尔值
### isLowMemoryMode() {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```


是否启用低内存转换模式

**退货：**
boolean - 布尔值
### isPageByPageFontProcess() {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```


是否启用了逐页基础模式的字体分析

默认值 = 假

**退货：**
boolean - 布尔值
### isTransferInfo() {#isTransferInfo--}
```
public final boolean isTransferInfo()
```


获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认情况下为真。

**退货：**
boolean - 布尔值
### isTransparencyIgnore() {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```


默认值 FALSE 和透明颜色将继续保持文档外观。值为 TRUE 透明颜色将转换为非透明颜色，可以覆盖一些对象。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlignStrategy(byte alignStrategy) {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```


对齐文本的策略。仅当标志 AlignText 设置为 true 时，此参数才有意义。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| alignStrategy | byte | SegmentAlignStrategy 元素 |

### setAlignText(boolean value) {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```


此标志控制转换文档中的文本对齐方式。默认情况下，文档转换不会影响文本对齐并保持文本原样。但在某些情况下，字体替换会导致转换后的文档中出现文本重叠或额外空格。设置此标志后，将执行特殊对齐操作。此标志应仅针对存在重叠文本或额外文本空间问题的文档设置，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAsyncImageStreamsConversionMode(boolean value) {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```


获取/设置异步模式下图像流的运行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setConvertSoftMaskAction(int value) {#setConvertSoftMaskAction-int-}
```
public final void setConvertSoftMaskAction(int value)
```


带有软蒙版的图像的动作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setErrorAction(int value) {#setErrorAction-int-}
```
public void setErrorAction(int value)
```


无法转换的对象的操作

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ConvertErrorAction 元素 |

### setExcludeFontsStrategy(byte value) {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```


排除多余字体并减小文档文件大小的策略。只有当标志 OptimizeFileSize 设置为 true 时，此参数才有意义。默认情况下，使用 SubsetFonts 和 RemoveDuplicatedFonts 策略组合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 布尔值 |

### setFormat(PdfFormat value) {#setFormat-com.aspose.pdf.PdfFormat-}
```
public void setFormat(PdfFormat value)
```


PDF 格式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setIccProfileFileName(String value) {#setIccProfileFileName-java.lang.String-}
```
public void setIccProfileFileName(String value)
```


设置 icc 配置文件名称的文件名。如果为 null，则使用默认的 icc 配置文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setLogFileName(String value) {#setLogFileName-java.lang.String-}
```
public void setLogFileName(String value)
```


将存储评论的文件路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setLogStream(OutputStream value) {#setLogStream-java.io.OutputStream-}
```
public void setLogStream(OutputStream value)
```


将存储评论的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setLowMemoryMode(boolean value) {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```


是否启用低内存转换模式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOptimizeFileSize(boolean value) {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```


设置一个启用/禁用特殊转换模式的标志，以获取文件大小减小的 PDF/A 文档。

现在这个标志影响了PDF文档中使用的字体的优化，可能在未来，这个标志也会被用来打开其他数据结构的优化，比如图形。

设置此标志和模式可以显着减小文件大小，但同时会显着降低转换性能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPageByPageFontProcess(boolean b) {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```


启用逐页基础模式设置页面字体分析

默认值 = 假

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| b | boolean | 布尔值 |

### setPuaTextProcessingStrategy(int value) {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```


处理来自 unicode 专用区 (PUA) 的符号的策略。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PuaProcessingStrategy 元素 |

### setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value) {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
```
public void setSymbolicFontEncodingStrategy(PdfASymbolicFontEncodingStrategy value)
```


如果符号 TrueType 字体具有多个编码子表，则复制符号字体编码数据的策略。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfASymbolicFontEncodingStrategy](../../com.aspose.pdf/pdfasymbolicfontencodingstrategy) | PdfASymbolicFontEncodingStrategy 对象 |

### setTransferInfo(boolean value) {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```


获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认情况下为真。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTransparencyAction(int value) {#setTransparencyAction-int-}
```
public void setTransparencyAction(int value)
```


图像蒙版对象的操作

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ConvertTransparencyAction 元素 |

### setTransparencyIgnore(boolean value) {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```


默认值 FALSE 和透明颜色将继续保持文档外观。值为 TRUE 透明颜色将转换为非透明颜色，可以覆盖一些对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTransparencyResolution(int dpi) {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```


在转换透明图像期间设置分辨率。分辨率越高，转换速度越慢。默认值为 300。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| dpi | int | 分辨率值 |

### setUnicodeProcessingRules(ToUnicodeProcessingRules value) {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
```
public void setUnicodeProcessingRules(ToUnicodeProcessingRules value)
```


解决 unicode 映射问题的规则。可以为空。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ToUnicodeProcessingRules](../../com.aspose.pdf/tounicodeprocessingrules) | ToUnicodeProcessingRules 对象 |

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
