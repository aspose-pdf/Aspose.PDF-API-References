---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示使用统一转换方式（具有统一内部文档模型）的保存选项。"
type: docs
weight: 5420
url: /zh/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

此类表示使用统一转换方式（具有统一内部文档模型）的保存选项。

## 字段

| 字段 | 描述 |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | 在少量线程中处理页面。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | 表示在转换期间工作的内部进度事件处理器，将内部转换阶段的转换事件转换为外部总体进度事件。该类还会广播事件，以释放不再需要的资源。此内部类处理 PDF 到 APS 以及 APS 到 [其他格式] 的进度事件，以计算总体进度并向客户代码通报该总体进度事件。该类使用两种类型的事件：ApsToExternal 模型转换事件和 PDF 到 APS 的转换事件，以生成总体进度事件。导出包含三个阶段：1) PDF 到 APS，2) APS 识别，3) APS 导出到目标格式。构造函数允许调节转换的页面数量以及在总体进度中各阶段的大致比例。 |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | 此属性启用从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。值：{@code true} 时，文本将被提取到结果文档中；否则，{@code false}。 |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如用于 DOCS 格式的 MsWord）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置以消除该不期望的效果。注意！此质量优化通常会显著降低转换速度，因此请仅在真正必要时使用此选项。 |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> 此属性启用从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 </p>Value: {@code true} 时，文本将被提取到结果文档中；否则，{@code false}。 <hr> 默认值 == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | 表示在转换期间工作的内部进度事件处理器，将内部转换阶段的转换事件转换为外部总体进度事件。该类还会广播事件，以释放不再需要的资源。此内部类处理 PDF 到 APS 以及 APS 到 [其他格式] 的进度事件，以计算总体进度并向客户代码通报该总体进度事件。该类使用两种类型的事件：ApsToExternal 模型转换事件和 PDF 到 APS 的转换事件，以生成总体进度事件。导出包含三个阶段：1) PDF 到 APS，2) APS 识别，3) APS 导出到目标格式。构造函数允许调节转换的页面数量以及在总体进度中各阶段的大致比例。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如用于 DOCS 格式的 MsWord）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置以消除该不期望的效果。注意！此质量优化通常会显著降低转换速度，因此请仅在真正必要时使用此选项。 |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

在少量线程中处理页面。

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

表示在转换期间工作的内部进度事件处理器，将内部转换阶段的转换事件转换为外部总体进度事件。该类还会广播事件，以释放不再需要的资源。此内部类处理 PDF 到 APS 以及 APS 到 [其他格式] 的进度事件，以计算总体进度并向客户代码通报该总体进度事件。该类使用两种类型的事件：ApsToExternal 模型转换事件和 PDF 到 APS 的转换事件，以生成总体进度事件。导出包含三个阶段：1) PDF 到 APS，2) APS 识别，3) APS 导出到目标格式。构造函数允许调节转换的页面数量以及在总体进度中各阶段的大致比例。

**Returns:**
ConversionProgressEventsTranslator 实例

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

此属性启用从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。值：{@code true} 时，文本将被提取到结果文档中；否则，{@code false}。

**Returns:**
布尔值

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如用于 DOCS 格式的 MsWord）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置以消除该不期望的效果。注意！此质量优化通常会显著降低转换速度，因此请仅在真正必要时使用此选项。

**Returns:**
布尔值

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> 此属性启用从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 </p>Value: {@code true} 时，文本将被提取到结果文档中；否则，{@code false}。 <hr> 默认值 == false

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
表示在转换期间工作的内部进度事件处理器，将内部转换阶段的转换事件转换为外部总体进度事件。该类还会广播事件，以释放不再需要的资源。此内部类处理 PDF 到 APS 以及 APS 到 [其他格式] 的进度事件，以计算总体进度并向客户代码通报该总体进度事件。该类使用两种类型的事件：ApsToExternal 模型转换事件和 PDF 到 APS 的转换事件，以生成总体进度事件。导出包含三个阶段：1) PDF 到 APS，2) APS 识别，3) APS 导出到目标格式。构造函数允许调节转换的页面数量以及在总体进度中各阶段的大致比例。

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如用于 DOCS 格式的 MsWord）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置以消除该不期望的效果。注意！此质量优化通常会显著降低转换速度，因此请仅在真正必要时使用此选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | 布尔值 |
