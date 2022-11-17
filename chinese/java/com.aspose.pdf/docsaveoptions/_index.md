---
title: DocSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 Doc 格式的保存选项
type: docs
weight: 90
url: /zh/java/com.aspose.pdf/docsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**所有已实现的接口：**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

导出为 Doc 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocSaveOptions()](#DocSaveOptions--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [getFormat()](#getFormat--) | 获取输出格式 |
| [getImageResolutionX()](#getImageResolutionX--) | 转换后的图像 X 分辨率。 |
| [getImageResolutionY()](#getImageResolutionY--) | 转换后的图像 Y 分辨率。 |
| [getMaxDistanceBetweenTextLines()](#getMaxDistanceBetweenTextLines--) | 此参数用于将文本行分组为段落。 |
| [getMemorySaveModePath()](#getMemorySaveModePath--) | 定义在内存保存模式下转换时保存临时数据的路径（文件名或目录名）。 |
| [getMode()](#getMode--) | 识别模式。 |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [getRelativeHorizontalProximity()](#getRelativeHorizontalProximity--) | 在 Pdf 中，单词可能在内部用运算符表示，这些运算符通过独立打印单词的字母或音节来打印单词。 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isAddReturnToLineEnd()](#isAddReturnToLineEnd--) | 使用段落或换行符。 |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [isRecognizeBullets()](#isRecognizeBullets--) | 开启子弹识别。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddReturnToLineEnd(boolean value)](#setAddReturnToLineEnd-boolean-) | 使用段落或换行符 |
| [setBatchSize(int value)](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式对，则定义批量大小。 |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [setFormat(int value)](#setFormat-int-) | 设置输出格式 |
| [setImageResolutionX(int value)](#setImageResolutionX-int-) | 转换后的图像 X 分辨率。 |
| [setImageResolutionY(int value)](#setImageResolutionY-int-) | 转换后的图像 Y 分辨率。 |
| [setMaxDistanceBetweenTextLines(float value)](#setMaxDistanceBetweenTextLines-float-) | 此参数用于将文本行分组为段落。 |
| [setMemorySaveModePath(String value)](#setMemorySaveModePath-java.lang.String-) | 定义在内存保存模式下转换时保存临时数据的路径（文件名或目录名）。 |
| [setMode(int value)](#setMode-int-) | 识别模式。 |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [setRecognizeBullets(boolean value)](#setRecognizeBullets-boolean-) | 开启子弹识别。 |
| [setRelativeHorizontalProximity(float value)](#setRelativeHorizontalProximity-float-) | 在 Pdf 中，单词可能在内部用运算符表示，这些运算符通过独立打印单词的字母或音节来打印单词。 |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocSaveOptions() {#DocSaveOptions--}
```
public DocSaveOptions()
```


构造函数

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**退货：**
整数
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**退货：**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) ConversionProgressEventHandler 实例
### getFormat() {#getFormat--}
```
public int getFormat()
```


获取输出格式

**退货：**
int - DocFormat 元素
### getImageResolutionX() {#getImageResolutionX--}
```
public int getImageResolutionX()
```


转换后的图像 X 分辨率。

**退货：**
int - 整数值
### getImageResolutionY() {#getImageResolutionY--}
```
public int getImageResolutionY()
```


转换后的图像 Y 分辨率。

**退货：**
int - 整数值
### getMaxDistanceBetweenTextLines() {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```


此参数用于将文本行分组为段落。确定两个相对文本行之间的距离。以文本行高度的百分之百指定。

**退货：**
float - 浮点值
### getMemorySaveModePath() {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```


定义在内存保存模式下转换时保存临时数据的路径（文件名或目录名）。

**退货：**
java.lang.String - 字符串值
### getMode() {#getMode--}
```
public int getMode()
```


识别模式。

**退货：**
int - RecognitionMode 值
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**退货：**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator 实例
### getRelativeHorizontalProximity() {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```


在 Pdf 中，单词可能在内部用运算符表示，这些运算符通过独立打印单词的字母或音节来打印单词。因此，为了检测单词，有时我们需要检测实际上是单词的独立字符组。此设置定义文本元素（字母、音节）之间的空间宽度，在识别源 PDF 中的单词时必须将其视为单词之间的距离。 （至少在字母之间存在这种宽度的空白意味着文本元素属于不同的词）。它以字体大小为标准——1.0 表示 100% 的假定字的字体大小。注意！它仅在源 PDF 包含特定的很少使用的字体且无法从字体计算最佳值时使用。因此，在绝大多数情况下，此参数不会改变结果文档中的任何内容。

**退货：**
float - 相对接近度
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


数据保存格式。

**退货：**
[SaveFormat](../../com.aspose.pdf/saveformat) 保存格式值
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

**退货：**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback 值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isAddReturnToLineEnd() {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```


使用段落或换行符。

**退货：**
boolean - 布尔值。
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


获取布尔值，该值指示在文档保存到响应后将关闭响应对象。

**退货：**
boolean - 布尔值
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

**退货：**
boolean - 布尔值
### isRecognizeBullets() {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```


开启子弹识别。

**退货：**
boolean - 布尔值
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

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




### setAddReturnToLineEnd(boolean value) {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```


使用段落或换行符

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值。 |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


如果批量转换适用于源格式和目标格式对，则定义批量大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


设置布尔值，指示在文档保存到响应后将关闭响应对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void convertWithShowingProgress()
 {
     (new License()).setLicense("License\\Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("Booklet.doc", saveOptions);
     System.in.read();
 }
 public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.getEventType())
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             Console.WriteLine("%s  - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             Console.WriteLine("%s  - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             Console.WriteLine("%s  - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             Console.WriteLine("{0}  - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString()));
             break;
         default:
             break;
     }
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler 实例 |

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

--------------------

默认值 == 假

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


设置输出格式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | DocFormat 元素 |

### setImageResolutionX(int value) {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```


转换后的图像 X 分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setImageResolutionY(int value) {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```


转换后的图像 Y 分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setMaxDistanceBetweenTextLines(float value) {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```


此参数用于将文本行分组为段落。确定两个相对文本行之间的距离。以文本行高度的百分之百指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setMemorySaveModePath(String value) {#setMemorySaveModePath-java.lang.String-}
```
public final void setMemorySaveModePath(String value)
```


定义在内存保存模式下转换时保存临时数据的路径（文件名或目录名）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


识别模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | RecognitionMode值 |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator 实例 |

### setRecognizeBullets(boolean value) {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```


开启子弹识别。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRelativeHorizontalProximity(float value) {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```


在 Pdf 中，单词可能在内部用运算符表示，这些运算符通过独立打印单词的字母或音节来打印单词。因此，为了检测单词，有时我们需要检测实际上是单词的独立字符组。此设置定义文本元素（字母、音节）之间的空间宽度，在识别源 PDF 中的单词时必须将其视为单词之间的距离。 （至少在字母之间存在这种宽度的空白意味着文本元素属于不同的词）。它以字体大小为标准——1.0 表示 100% 的假定字的字体大小。注意！它仅在源 PDF 包含特定的很少使用的字体且无法从字体计算最佳值时使用。因此，在绝大多数情况下，此参数不会改变结果文档中的任何内容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 相对接近 |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | 布尔值 |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。

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
