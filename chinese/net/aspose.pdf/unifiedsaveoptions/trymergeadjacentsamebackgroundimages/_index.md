---
title: "UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages"
second_title: "Aspose.PDF for .NET API 参考"
description: "UnifiedSaveOptions 字段。有时 PDF 包含由多个相同的平铺背景图像相邻放置而构成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器，例如用于 DOCS 格式的 MsWord，可能会生成背景图像各部分之间的可见边界，因为它们的图像边缘平滑抗锯齿技术与 Acrobat Reader 不同。如果导出的文档出现此类同一背景图像各部分之间的可见边界，请尝试使用此设置以消除该不期望的效果。ATTENTION 此质量优化通常会显著减慢转换速度，请仅在确实必要时使用此选项。"
type: docs
weight: 40
url: /zh/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### 另请参见

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


