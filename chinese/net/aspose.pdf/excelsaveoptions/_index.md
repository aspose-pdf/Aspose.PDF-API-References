---
title: ExcelSaveOptions
second_title: Aspose.PDF for .NET API 参考
description: 保存导出到 Excel 格式的选项
type: docs
weight: 2120
url: /zh/net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class

保存导出到 Excel 格式的选项

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | 获取或设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | 这个属性开启了为带有 OCR 子层的 PDF 文档提取图像或文本 的功能。 |
| [Format](../../aspose.pdf/excelsaveoptions/format) { get; set; } | 输出格式 |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst) { get; set; } | 如果需要插入空白列作为工作表的第一列，则设置为 true。 默认值为 false；这意味着不会插入空白列。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets) { get; set; } | 如果需要最小化结果工作簿中的工作表数量，则设置为 true。 默认值为 false；这意味着将每个 PDF 页面保存为单独的工作表。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | 数据保存的格式。 |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets) { get; set; } | 设置为 true 以在文档中使用统一的列划分。 默认值为假；这意味着列划分将独立于每个页面。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | 回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | 有时 PDF 包含（页面或表格单元格的）背景图像 由多个相同的平铺背景图像构成，彼此相邻。 在这种情况下，目标格式的渲染器（对于 DOCS 格式的 Fe MsWord）有时会在部分背景图像之间生成 可见边界, 因为他们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。 如果导出的文档看起来在相同背景图像的 部分之间包含这样的可见边界，请尝试使用此设置来消除 不想要的效果。 注意！这种质量优化通常会减慢转换速度， 所以，请仅在真正需要时使用此选项。 |

### 也可以看看

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->