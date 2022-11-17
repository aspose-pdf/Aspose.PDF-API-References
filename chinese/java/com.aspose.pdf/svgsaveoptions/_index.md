---
title: SvgSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 SVG 格式的保存选项
type: docs
weight: 344
url: /zh/java/com.aspose.pdf/svgsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class SvgSaveOptions extends UnifiedSaveOptions
```

导出为 SVG 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgSaveOptions()](#SvgSaveOptions--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomStrategyOfEmbeddedImagesSaving()](#getCustomStrategyOfEmbeddedImagesSaving--) | 此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理嵌入到保存的 SVG 中的已创建引用外部图像文件（如嵌入的 BMP 或 JPEG）。 |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [isCompressOutputToZipArchive()](#isCompressOutputToZipArchive--) | 指定是否将输出创建为一个 zip 存档。 |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [isScaleToPixels()](#isScaleToPixels--) | 指定是否将输出文档从印刷点缩放到像素。 |
| [isTreatTargetFileNameAsDirectory()](#isTreatTargetFileNameAsDirectory--) | 此选项定义是否将创建与请求的输出文件同名的目标目录（如果不存在）而不是请求的输出文件本身。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setCompressOutputToZipArchive(boolean compressOutputToZipArchive)](#setCompressOutputToZipArchive-boolean-) | 指定是否将输出创建为一个 zip 存档。 |
| [setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | 此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理嵌入到保存的 SVG 中的已创建引用外部图像文件（如嵌入的 BMP 或 JPEG）。 |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [setScaleToPixels(boolean scaleToPixels)](#setScaleToPixels-boolean-) | 指定是否将输出文档从印刷点缩放到像素。 |
| [setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)](#setTreatTargetFileNameAsDirectory-boolean-) | 此选项定义是否将创建与请求的输出文件同名的目标目录（如果不存在）而不是请求的输出文件本身。 |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgSaveOptions() {#SvgSaveOptions--}
```
public SvgSaveOptions()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCustomStrategyOfEmbeddedImagesSaving() {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```


此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理嵌入到保存的 SVG 中的已创建引用外部图像文件（如嵌入的 BMP 或 JPEG）。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的理想 URI 的字符串。如果由于某种原因必须由转换器代码本身而不是自定义代码来处理这个或那个文件，请在“imageSavingInfo”参数变量的自定义代码标志“CustomProcessingCancelled”中设置它向转换器发出信号，表明所有必要的处理步骤该资源必须在转换器本身中完成，就好像没有任何外部自定义代码一样。

**退货：**
[EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) - EmbeddedImagesSavingStrategy 实例
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**退货：**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator 实例
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
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


获取布尔值，该值指示在文档保存到响应后将关闭响应对象。

**退货：**
boolean - 布尔值
### isCompressOutputToZipArchive() {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```


指定是否将输出创建为一个 zip 存档。请参考“TreatTargetFileNameAsDirectory”选项的评论，以查看多页源文档页面 svg 文件的命名规则，这些规则也适用于压缩的输出文件集。

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
### isScaleToPixels() {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```


指定是否将输出文档从印刷点缩放到像素。

**退货：**
boolean - 布尔值
### isTreatTargetFileNameAsDirectory() {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```


此选项定义是否将创建与请求的输出文件同名的目标目录（如果不存在）而不是请求的输出文件本身。因此，该目录将包含页面的所有输出 SVG 图像（如下所述）。如果不是，第一个页面以外的页面的输出文件将在请求的目录中作为主输出文件创建，但将包含在文件名后缀中\_[2...n]，即由页码定义，如果您定义输出文件“C:\\Aspose测试\\output.svg" 和输出将包含几个页面的 svg 文件，然后页面文件也将在目录 "C:\\Aspose测试\\" 并命名为 'output.svg', 'output\_2.svg', '输出\_3.svg'等

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




### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


设置布尔值，指示在文档保存到响应后将关闭响应对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCompressOutputToZipArchive(boolean compressOutputToZipArchive) {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```


指定是否将输出创建为一个 zip 存档。请参考“TreatTargetFileNameAsDirectory”选项的评论，以查看多页源文档页面 svg 文件的命名规则，这些规则也适用于压缩的输出文件集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| compressOutputToZipArchive | boolean | 布尔值 |

### setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving) {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
```
public void setCustomStrategyOfEmbeddedImagesSaving(SvgSaveOptions.EmbeddedImagesSavingStrategy customStrategyOfEmbeddedImagesSaving)
```


此字段可以包含在转换期间必须使用（如果存在）的保存策略，以自定义处理嵌入到保存的 SVG 中的已创建引用外部图像文件（如嵌入的 BMP 或 JPEG）。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的理想 URI 的字符串。如果由于某种原因必须由转换器代码本身而不是自定义代码来处理这个或那个文件，请在“imageSavingInfo”参数变量的自定义代码标志“CustomProcessingCancelled”中设置它向转换器发出信号，表明所有必要的处理步骤该资源必须在转换器本身中完成，就好像没有任何外部自定义代码一样。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customStrategyOfEmbeddedImagesSaving | [EmbeddedImagesSavingStrategy](../../com.aspose.pdf/embeddedimagessavingstrategy) | EmbeddedImagesSavingStrategy 实例 |

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

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator 实例 |

### setScaleToPixels(boolean scaleToPixels) {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```


指定是否将输出文档从印刷点缩放到像素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| scaleToPixels | boolean | 布尔值 |

### setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory) {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```


此选项定义是否将创建与请求的输出文件同名的目标目录（如果不存在）而不是请求的输出文件本身。因此，该目录将包含页面的所有输出 SVG 图像（如下所述）。如果不是，第一个页面以外的页面的输出文件将在请求的目录中作为主输出文件创建，但将包含在文件名后缀中\_[2...n]，即由页码定义，如果您定义输出文件“C:\\Aspose测试\\output.svg" 和输出将包含几个页面的 svg 文件，然后页面文件也将在目录 "C:\\Aspose测试\\" 并命名为 'output.svg', 'output\_2.svg', '输出\_3.svg'等

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| treatTargetFileNameAsDirectory | boolean | 布尔值 |

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
