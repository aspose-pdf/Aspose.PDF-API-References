---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 Doc 格式的保存选项"
type: docs
weight: 1030
url: /zh/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

导出为 Doc 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | 获取输出格式 |
| [getImageResolutionX](#getImageResolutionX--) | 已转换图像的 X 分辨率。 |
| [getImageResolutionY](#getImageResolutionY--) | 已转换图像的 Y 分辨率。 |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | 此参数用于将文本行分组为段落。确定两行相对文本行之间可以相距多远。以文本行高度的百分之百为单位指定。 |
| [getMemorySaveModePath](#getMemorySaveModePath--) | 定义在内存保存模式下转换时用于保存临时数据的路径（文件名或目录名）。 |
| [getMode](#getMode--) | 识别模式。 |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | 在 PDF 中，单词可能通过操作符内部表示为逐字母或音节独立打印的方式。因此，为了检测单词，有时需要检测实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空格宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该宽度相对于字体大小进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定罕用字体且无法从字体计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有影响。 |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | 用于段落或换行符。 |
| [isConvertType3Fonts](#isConvertType3Fonts--) | 获取或设置对 Type3 字体的转换。在 Type3 字体中，字形由图形操作符流定义。这意味着在 DOC/DOCX 输出中我们会看到图像而不是文本。将此标志设为 true 可将 Type3 字体转换为 TTF，并在生成的文件中获得文本。 |
| [isRecognizeBullets](#isRecognizeBullets--) | 开启对项目符号的识别。 |
| [isReSaveFonts](#isReSaveFonts--) | 获取或设置重新保存字体的过程。如果设为 true，则在每页重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果想提升性能，可将此选项设为 false。默认值为 true； |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | 使用段落或换行符 |
| [setBatchSize](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | 获取或设置对 Type3 字体的转换。在 Type3 字体中，字形由图形操作符流定义。这意味着在 DOC/DOCX 输出中我们会看到图像而不是文本。将此标志设为 true 可将 Type3 字体转换为 TTF，并在生成的文件中获得文本。 |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件，例如。 |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | 设置输出格式 |
| [setImageResolutionX](#setImageResolutionX-int-) | 已转换图像的 X 分辨率。 |
| [setImageResolutionY](#setImageResolutionY-int-) | 已转换图像的 Y 分辨率。 |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | 此参数用于将文本行分组为段落。确定两行相对文本行之间可以相距多远。以文本行高度的百分之百为单位指定。 |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | 定义在内存保存模式下转换时用于保存临时数据的路径（文件名或目录名）。 |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | 识别模式。 |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | 开启对项目符号的识别。 |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | 在 PDF 中，单词可能通过操作符内部表示为逐字母或音节独立打印的方式。因此，为了检测单词，有时需要检测实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空格宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该宽度相对于字体大小进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定罕用字体且无法从字体计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有影响。 |
| [setReSaveFonts](#setReSaveFonts-boolean-) | 获取或设置重新保存字体的过程。如果设为 true，则在每页重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果想提升性能，可将此选项设为 false。默认值为 true； |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

构造函数

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Returns:**
int 值

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler 实例

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

获取输出格式

**Returns:**
DocFormat 元素 @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

已转换图像的 X 分辨率。

**Returns:**
int 值

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

已转换图像的 Y 分辨率。

**Returns:**
int 值

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

此参数用于将文本行分组为段落。确定两行相对文本行之间可以相距多远。以文本行高度的百分之百为单位指定。

**Returns:**
float 值

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

定义在内存保存模式下转换时用于保存临时数据的路径（文件名或目录名）。

**Returns:**
字符串值

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

识别模式。

**Returns:**
RecognitionMode 值 @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

在 PDF 中，单词可能通过操作符内部表示为逐字母或音节独立打印的方式。因此，为了检测单词，有时需要检测实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空格宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该宽度相对于字体大小进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定罕用字体且无法从字体计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有影响。

**Returns:**
相对接近度

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

用于段落或换行符。

**Returns:**
布尔值。

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

获取或设置对 Type3 字体的转换。在 Type3 字体中，字形由图形操作符流定义。这意味着在 DOC/DOCX 输出中我们会看到图像而不是文本。将此标志设为 true 可将 Type3 字体转换为 TTF，并在生成的文件中获得文本。

**Returns:**
布尔值

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

开启对项目符号的识别。

**Returns:**
布尔值

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

获取或设置重新保存字体的过程。如果设为 true，则在每页重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果想提升性能，可将此选项设为 false。默认值为 true；

**Returns:**
布尔值

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

使用段落或换行符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值。 |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

获取或设置对 Type3 字体的转换。在 Type3 字体中，字形由图形操作符流定义。这意味着在 DOC/DOCX 输出中我们会看到图像而不是文本。将此标志设为 true 可将 Type3 字体转换为 TTF，并在生成的文件中获得文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
此处理程序可用于处理转换进度事件，例如。

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
设置输出格式

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

已转换图像的 X 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

已转换图像的 Y 分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

此参数用于将文本行分组为段落。确定两行相对文本行之间可以相距多远。以文本行高度的百分之百为单位指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
定义在内存保存模式下转换时用于保存临时数据的路径（文件名或目录名）。

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
识别模式。

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

开启对项目符号的识别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

在 PDF 中，单词可能通过操作符内部表示为逐字母或音节独立打印的方式。因此，为了检测单词，有时需要检测实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空格宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该宽度相对于字体大小进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定罕用字体且无法从字体计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有影响。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 相对接近度 |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

获取或设置重新保存字体的过程。如果设为 true，则在每页重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果想提升性能，可将此选项设为 false。默认值为 true；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
