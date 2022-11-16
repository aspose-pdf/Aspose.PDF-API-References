---
title: PptxSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 SVG 格式的保存选项
type: docs
weight: 292
url: /zh/java/com.aspose.pdf/pptxsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class PptxSaveOptions extends UnifiedSaveOptions
```

导出为 SVG 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PptxSaveOptions()](#PptxSaveOptions--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [getImageResolution()](#getImageResolution--) | 获取或设置图像分辨率 (dpi)。 |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getSeparateImages()](#getSeparateImages--) | 如果设置为 true 则图像与所有其他图形分开 |
| [getSlidesAsImages()](#getSlidesAsImages--) | 如果设置为 true 则所有内容都被识别为图像（每页一个） |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [isOptimizeTextBoxes()](#isOptimizeTextBoxes--) | 切换文本列识别 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | 此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是： |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [setImageResolution(int value)](#setImageResolution-int-) | 获取或设置图像分辨率 (dpi)。 |
| [setOptimizeTextBoxes(boolean value)](#setOptimizeTextBoxes-boolean-) | 切换文本列识别 |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [setSeparateImages(boolean value)](#setSeparateImages-boolean-) | 如果设置为 true 则图像与所有其他图形分开 |
| [setSlidesAsImages(boolean value)](#setSlidesAsImages-boolean-) | 如果设置为 true 则所有内容都被识别为图像（每页一个） |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PptxSaveOptions() {#PptxSaveOptions--}
```
public PptxSaveOptions()
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
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.setCustomProgressHandler(new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole));
     doc.save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**退货：**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) ConversionProgressEventHandler 实例
### getImageResolution() {#getImageResolution--}
```
public final int getImageResolution()
```


获取或设置图像分辨率 (dpi)。默认为 192 dpi。

**退货：**
int - 整数值
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
### getSeparateImages() {#getSeparateImages--}
```
public boolean getSeparateImages()
```


如果设置为 true 则图像与所有其他图形分开

**退货：**
boolean - 布尔值
### getSlidesAsImages() {#getSlidesAsImages--}
```
public boolean getSlidesAsImages()
```


如果设置为 true 则所有内容都被识别为图像（每页一个）

**退货：**
boolean - 布尔值
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
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

**退货：**
boolean - 布尔值
### isOptimizeTextBoxes() {#isOptimizeTextBoxes--}
```
public final boolean isOptimizeTextBoxes()
```


切换文本列识别

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

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler value)
```


此处理程序可用于处理转换进度事件 fe 它可用于显示进度条或有关当前已处理页面数量的消息，在控制台上显示进度的处理程序代码示例是：

--------------------

```
public static void ConvertWithShowingProgress()
 {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("input.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new HtmlSaveOptions.ConversionProgressEventHandler(ShowProgressOnConsole);
     doc.Save("output.html", saveOptions);

 }
 public static void ShowProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
 {
     switch (eventInfo.EventType)
     {
         case HtmlSaveOptions.ProgressEventType.TotalProgress:
             System.out.println(string.Format("{0}  - Conversion progress : {1}% .", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
             System.out.println(string.Format("{0}  - Source page {1} of {2} analyzed.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
             System.out.println(string.Format("{0}  - Result page's {1} of {2} layout created.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
             System.out.println(string.Format("{0}  - Result page {1} of {2} exported.", DateTime.Now.ToLongTimeString(), eventInfo.Value.ToString(), eventInfo.MaxValue.ToString()));
             break;
         default:
             break;
     }
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler 实例 |

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

### setImageResolution(int value) {#setImageResolution-int-}
```
public final void setImageResolution(int value)
```


获取或设置图像分辨率 (dpi)。默认为 192 dpi。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setOptimizeTextBoxes(boolean value) {#setOptimizeTextBoxes-boolean-}
```
public final void setOptimizeTextBoxes(boolean value)
```


切换文本列识别

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

### setSeparateImages(boolean value) {#setSeparateImages-boolean-}
```
public void setSeparateImages(boolean value)
```


如果设置为 true 则图像与所有其他图形分开

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSlidesAsImages(boolean value) {#setSlidesAsImages-boolean-}
```
public void setSlidesAsImages(boolean value)
```


如果设置为 true 则所有内容都被识别为图像（每页一个）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
