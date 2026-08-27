---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于转换 PDF 文档的选项集合。"
type: docs
weight: 3730
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

表示用于转换 PDF 文档的选项集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 构造函数 |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | 构造函数 |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 构造函数 |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | 构造函数 |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | 构造函数 |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | 对齐文本的策略。仅当标志 {@code AlignText} 设置为 true 时此参数才有意义。 |
| [getAlignText](#getAlignText--) | 此标志控制转换后文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，保持文本原样。但在某些情况下，字体替换会导致转换后文档出现文本重叠或额外空格。设置此标志后，将执行特殊的对齐操作。仅应在文本出现重叠或额外空格问题的文档中使用此标志，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。 |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | 获取或设置 PDF 格式转换期间的自动标记设置。自动标记设置用于配置自动标记过程的行为，该过程通常用于在转换为特定 PDF 格式时提升 PDF 文档的可访问性和结构。 |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | 软掩码图像的操作。 |
| [getDefault](#getDefault--) | 获取具有默认参数的 PdfFormatConversionOptions 对象 |
| [getErrorAction](#getErrorAction--) | 无法转换的对象的操作 |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | 用于排除多余字体并减小文档文件大小的策略。仅当标志 {@code OptimizeFileSize} 设置为 true 时此参数才有意义。默认情况下使用 {@code SubsetFonts} 和 {@code RemoveDuplicatedFonts} 组合策略。 |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | 在某些字体无法嵌入 PDF 文档时的选项。 |
| [getFormat](#getFormat--) | PDF 格式。 |
| [getIccProfileFileName](#getIccProfileFileName--) | 获取 ICC 配置文件的文件名。如果为 null，则使用默认的 ICC 配置文件。 |
| [getLogFileName](#getLogFileName--) | 存储评论的文件路径。 |
| [getLogStream](#getLogStream--) | 存储评论的流。 |
| [getNonSpecificationCases](#getNonSpecificationCases--) | 保存用于控制 PDF/A 转换过程的标志，以应对源文档不符合 PDF/A 规范的情况。 |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | 此属性为输出属性。它保存上一次 PDF/A 转换时在计算机上未找到的所有字体（字体名称）。 |
| [getOptimizeFileSize](#getOptimizeFileSize--) | 获取一个标志，用于启用/禁用特殊转换模式，以获得文件大小更小的 PDF/A 文档。当前此标志影响 PDF 文档中使用的字体优化，未来可能还用于开启对其他数据结构（如图形）的优化。该标志与模式的组合可以显著减小文件大小，但同时也可能显著降低转换性能。 |
| [getOutputIntent](#getOutputIntent--) | 获取或设置 PDF 格式转换的 {@link OutputIntent}。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）指定 PDF 文档准备的目标输出设备或条件。它用于确保文档中的颜色在目标设备上正确呈现。 |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | 处理 Unicode 私用区 (PUA) 符号的策略。 |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | 当符号 TrueType 字体拥有多个编码子表时，复制符号字体编码数据的策略。 |
| [getTransparencyAction](#getTransparencyAction--) | 图像掩码对象的操作 |
| [getTransparencyResolution](#getTransparencyResolution--) | 设置透明图像转换时的分辨率。分辨率越高，转换速度越慢。默认值为 300。 |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | 解决 Unicode 映射问题的规则。可以为 null。 |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | 获取/设置异步模式下图像流的运行。 |
| [isLowMemoryMode](#isLowMemoryMode--) | 是否启用低内存转换模式 |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | 是否启用按页分析字体模式 默认值 = false |
| [isTransferInfo](#isTransferInfo--) | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认值为 True。 |
| [isTransparencyIgnore](#isTransparencyIgnore--) | 默认值 FALSE，透明颜色将被保留以保持文档外观。值为 TRUE 时，透明颜色将转换为非透明，某些对象可能被覆盖。 |
| [setAlignStrategy](#setAlignStrategy-byte-) | 对齐文本的策略。仅当标志 {@code AlignText} 设置为 true 时此参数才有意义。 |
| [setAlignText](#setAlignText-boolean-) | 此标志控制转换后文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，保持文本原样。但在某些情况下，字体替换会导致转换后文档出现文本重叠或额外空格。设置此标志后，将执行特殊的对齐操作。仅应在文本出现重叠或额外空格问题的文档中使用此标志，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。 |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | 获取/设置异步模式下图像流的运行。 |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | 获取或设置 PDF 格式转换期间的自动标记设置。自动标记设置用于配置自动标记过程的行为，该过程通常用于在转换为特定 PDF 格式时提升 PDF 文档的可访问性和结构。 |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | 软掩码图像的操作。 |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | 无法转换的对象的操作 |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | 用于排除多余字体并减小文档文件大小的策略。仅当标志 {@code OptimizeFileSize} 设置为 true 时此参数才有意义。默认情况下使用 {@code SubsetFonts} 和 {@code RemoveDuplicatedFonts} 组合策略。 |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF 格式。 |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | 设置 icc 配置文件的文件名。如果为 null，则使用默认 icc 配置文件。 |
| [setLogFileName](#setLogFileName-java.lang.String-) | 存储评论的文件路径。 |
| [setLogStream](#setLogStream-java.io.OutputStream-) | 存储评论的流。 |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | 是否启用低内存转换模式 |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | 设置一个标志，用于启用/禁用特殊转换模式以获取文件大小更小的 PDF/A 文档。当前此标志影响 PDF 文档中使用的字体优化，未来可能还用于对其他数据结构（如图形）进行优化。该标志与模式的组合可以显著减小文件大小，但同时可能显著降低转换性能。 |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | 获取或设置 PDF 格式转换的 {@link OutputIntent}。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）指定 PDF 文档准备的目标输出设备或条件。它用于确保文档中的颜色在目标设备上正确呈现。 |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | 设置按页分析字体模式 已启用 默认值 = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | 处理 Unicode 私用区 (PUA) 符号的策略。 |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | 当符号 TrueType 字体拥有多个编码子表时，复制符号字体编码数据的策略。 |
| [setTransferInfo](#setTransferInfo-boolean-) | 获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认值为 True。 |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | 图像掩码对象的操作 |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | 默认值 FALSE，透明颜色将被保留以保持文档外观。值为 TRUE 时，透明颜色将转换为非透明，某些对象可能被覆盖。 |
| [setTransparencyResolution](#setTransparencyResolution-int-) | 设置透明图像转换时的分辨率。分辨率越高，转换速度越慢。默认值为 300。 |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | 解决 Unicode 映射问题的规则。可以为 null。 |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
构造函数

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
构造函数

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
构造函数

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
构造函数

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
构造函数

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
构造函数

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

对齐文本的策略。仅当标志 {@code AlignText} 设置为 true 时此参数才有意义。

**Returns:**
SegmentAlignStrategy 元素 @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

此标志控制转换后文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，保持文本原样。但在某些情况下，字体替换会导致转换后文档出现文本重叠或额外空格。设置此标志后，将执行特殊的对齐操作。仅应在文本出现重叠或额外空格问题的文档中使用此标志，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。

**Returns:**
布尔值

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

获取或设置 PDF 格式转换期间的自动标记设置。自动标记设置用于配置自动标记过程的行为，该过程通常用于在转换为特定 PDF 格式时提升 PDF 文档的可访问性和结构。

**Returns:**
AutoTaggingSettings 实例

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

软掩码图像的操作。

**Returns:**
int 值

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

获取具有默认参数的 PdfFormatConversionOptions 对象

**Returns:**
PdfFormatConversionOptions 对象

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

无法转换的对象的操作

**Returns:**
ConvertErrorAction 元素 @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

用于排除多余字体并减小文档文件大小的策略。仅当标志 {@code OptimizeFileSize} 设置为 true 时此参数才有意义。默认情况下使用 {@code SubsetFonts} 和 {@code RemoveDuplicatedFonts} 组合策略。

**Returns:**
byte 值 @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

在某些字体无法嵌入 PDF 文档时的选项。

**Returns:**
FontEmbeddingOptions 对象

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF 格式。

**Returns:**
PdfFormat 元素 @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

获取 ICC 配置文件的文件名。如果为 null，则使用默认的 ICC 配置文件。

**Returns:**
字符串对象

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

存储评论的文件路径。

**Returns:**
字符串对象

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

存储评论的流。

**Returns:**
OutputStream 对象

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

保存用于控制 PDF/A 转换过程的标志，以应对源文档不符合 PDF/A 规范的情况。

**Returns:**
PdfANonSpecificationFlags 对象

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

此属性为输出属性。它保存上一次 PDF/A 转换时在计算机上未找到的所有字体（字体名称）。

**Returns:**
字符串数组

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

获取一个标志，用于启用/禁用特殊转换模式，以获得文件大小更小的 PDF/A 文档。当前此标志影响 PDF 文档中使用的字体优化，未来可能还用于开启对其他数据结构（如图形）的优化。该标志与模式的组合可以显著减小文件大小，但同时也可能显著降低转换性能。

**Returns:**
布尔值

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

获取或设置 PDF 格式转换的 {@link OutputIntent}。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）指定 PDF 文档准备的目标输出设备或条件。它用于确保文档中的颜色在目标设备上正确呈现。

**Returns:**
OutputIntent 实例

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

处理 Unicode 私用区 (PUA) 符号的策略。

**Returns:**
PuaProcessingStrategy 元素 @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

当符号 TrueType 字体拥有多个编码子表时，复制符号字体编码数据的策略。

**Returns:**
PdfASymbolicFontEncodingStrategy 对象

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

图像掩码对象的操作

**Returns:**
ConvertTransparencyAction 元素 @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

设置透明图像转换时的分辨率。分辨率越高，转换速度越慢。默认值为 300。

**Returns:**
分辨率值

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

解决 Unicode 映射问题的规则。可以为 null。

**Returns:**
ToUnicodeProcessingRules 对象

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

获取/设置异步模式下图像流的运行。

**Returns:**
布尔值

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

是否启用低内存转换模式

**Returns:**
布尔值

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

是否启用按页分析字体模式 默认值 = false

**Returns:**
布尔值

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认值为 True。

**Returns:**
布尔值

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

默认值 FALSE，透明颜色将被保留以保持文档外观。值为 TRUE 时，透明颜色将转换为非透明，某些对象可能被覆盖。

**Returns:**
布尔值

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

对齐文本的策略。仅当标志 {@code AlignText} 设置为 true 时此参数才有意义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy 元素 @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

此标志控制转换后文档中的文本对齐。默认情况下，文档转换不会影响文本对齐，保持文本原样。但在某些情况下，字体替换会导致转换后文档出现文本重叠或额外空格。设置此标志后，将执行特殊的对齐操作。仅应在文本出现重叠或额外空格问题的文档中使用此标志，因为使用此标志会降低性能，并且在某些情况下可能会损坏文本内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

获取/设置异步模式下图像流的运行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
获取或设置 PDF 格式转换期间的自动标记设置。自动标记设置用于配置自动标记过程的行为，该过程通常用于在转换为特定 PDF 格式时提升 PDF 文档的可访问性和结构。

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
软掩码图像的操作。

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
无法转换的对象的操作

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

用于排除多余字体并减小文档文件大小的策略。仅当标志 {@code OptimizeFileSize} 设置为 true 时此参数才有意义。默认情况下使用 {@code SubsetFonts} 和 {@code RemoveDuplicatedFonts} 组合策略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF 格式。

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
设置 icc 配置文件的文件名。如果为 null，则使用默认 icc 配置文件。

### setLogFileName {#setLogFileName-java.lang.String-}
存储评论的文件路径。

### setLogStream {#setLogStream-java.io.OutputStream-}
存储评论的流。

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

是否启用低内存转换模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

设置一个标志，用于启用/禁用特殊转换模式以获取文件大小更小的 PDF/A 文档。当前此标志影响 PDF 文档中使用的字体优化，未来可能还用于对其他数据结构（如图形）进行优化。该标志与模式的组合可以显著减小文件大小，但同时可能显著降低转换性能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
获取或设置 PDF 格式转换的 {@link OutputIntent}。{@code OutputIntent}（{@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}）指定 PDF 文档准备的目标输出设备或条件。它用于确保文档中的颜色在目标设备上正确呈现。

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

设置按页分析字体模式 已启用 默认值 = false

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| b |  | 布尔值 |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

处理 Unicode 私用区 (PUA) 符号的策略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PuaProcessingStrategy 元素 @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
当符号 TrueType 字体拥有多个编码子表时，复制符号字体编码数据的策略。

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

获取或设置在转换为 PDF 2.0 时是否将数据从 Info 传递到 Metadata。默认值为 True。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
图像掩码对象的操作

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

默认值 FALSE，透明颜色将被保留以保持文档外观。值为 TRUE 时，透明颜色将转换为非透明，某些对象可能被覆盖。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

设置透明图像转换时的分辨率。分辨率越高，转换速度越慢。默认值为 300。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| DPI |  | 分辨率值 |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
解决 Unicode 映射问题的规则。可以为 null。
