---
title: ExcelSaveOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 导出为 Excel 格式的保存选项
type: docs
weight: 101
url: /zh/java/com.aspose.pdf/excelsaveoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

导出为 Excel 格式的保存选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExcelSaveOptions()](#ExcelSaveOptions--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | 输出格式。 |
| [getMinimizeTheNumberOfWorksheets()](#getMinimizeTheNumberOfWorksheets--) | 如果您需要最小化生成的工作簿中的工作表数量，请设置为真。 |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [getSaveFormat()](#getSaveFormat--) | 数据保存格式。 |
| [getWarningHandler()](#getWarningHandler--) | 回调以处理生成的任何警告。 |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | 获取布尔值，该值指示在文档保存到响应后将关闭响应对象。 |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [isInsertBlankColumnAtFirst()](#isInsertBlankColumnAtFirst--) | 如果您需要禁止插入空白列作为工作表的第一列，请设置为 false。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [isUniformWorksheets()](#isUniformWorksheets--) | 设置为 true 以在文档中使用统一的列划分。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | 设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | 此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。 |
| [setFormat(int value)](#setFormat-int-) | 输出格式 |
| [setInsertBlankColumnAtFirst(boolean value)](#setInsertBlankColumnAtFirst-boolean-) | 如果您需要禁止插入空白列作为工作表的第一列，请设置为 false。 |
| [setMinimizeTheNumberOfWorksheets(boolean value)](#setMinimizeTheNumberOfWorksheets-boolean-) | 如果您需要最小化生成的工作簿中的工作表数量，请设置为真。 |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，并将内部转换阶段的转换事件转换为外部总进度事件此外，类广播允许释放不再需要的资源的事件该内部类处理 PDF 到 APS 和 APS 到[Other format] progress 计算总进度并通知客户代码关于总进度事件此类使用两种类型的事件：ApsTo外部模型转换和事件转换Pdf到APS以生成总进度事件导出有三个阶段：1）Pdf到Aps 2）aps识别3\_ Aps 导出到目标格式 构造器允许调整转换了多少页面以及这个或那个阶段在总进度中的近似部分 |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setUniformWorksheets(boolean value)](#setUniformWorksheets-boolean-) | 设置为 true 以在文档中使用统一的列划分。 |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExcelSaveOptions() {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
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
### getFormat() {#getFormat--}
```
public int getFormat()
```


输出格式。

返回 ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003 或 ExcelSaveOptions.ExcelFormat.XLSX 或 ExcelSaveOptions.ExcelFormat.CSV 

**退货：**
int - ExcelFormat 元素
### getMinimizeTheNumberOfWorksheets() {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```


如果您需要最小化生成的工作簿中的工作表数量，请设置为真。默认值为假；这意味着将每个 PDF 页面保存为单独的工作表。

**退货：**
boolean - 布尔值
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
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


此属性打开了使用 OCR 子层为 PDF 文档提取图像或文本的功能。

Value：结果文档中将提取真实的文本；否则，假的。

**退货：**
boolean - 布尔值
### isInsertBlankColumnAtFirst() {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```


如果您需要禁止插入空白列作为工作表的第一列，请设置为 false。默认值为真；这意味着将插入空白列。

**退货：**
boolean - 布尔值
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**退货：**
boolean - 布尔值
### isUniformWorksheets() {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```


设置为 true 以在文档中使用统一的列划分。默认值为假；这意味着列划分将独立于每个页面。

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


输出格式

使用 ExcelSaveOptions.ExcelFormat.XMLSpreadSheet2003 或 ExcelSaveOptions.ExcelFormat.XLSX 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ExcelFormat 元素 |

### setInsertBlankColumnAtFirst(boolean value) {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```


如果您需要禁止插入空白列作为工作表的第一列，请设置为 false。默认值为真；这意味着将插入空白列。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMinimizeTheNumberOfWorksheets(boolean value) {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```


如果您需要最小化生成的工作簿中的工作表数量，请设置为真。默认值为假；这意味着将每个 PDF 页面保存为单独的工作表。

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

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | 布尔值 |

### setUniformWorksheets(boolean value) {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```


设置为 true 以在文档中使用统一的列划分。默认值为假；这意味着列划分将独立于每个页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
