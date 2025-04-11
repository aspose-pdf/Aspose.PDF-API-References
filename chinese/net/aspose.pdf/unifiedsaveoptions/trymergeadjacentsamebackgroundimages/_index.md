---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: UnifiedSaveOptions 字段。有时 PDF 包含由几个相同的平铺背景图像构成的页面或表格单元格的背景图像，这些图像彼此靠近。在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会在背景图像的部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置来消除这种不必要的效果。注意！这种质量优化通常会显著减慢转换速度，因此请仅在确实必要时使用此选项。
type: docs
weight: 40
url: /zh/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages 字段

有时 PDF 包含由几个相同的平铺背景图像构成的页面或表格单元格的背景图像，这些图像彼此靠近。在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会在背景图像的部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置来消除这种不必要的效果。注意！这种质量优化通常会显著减慢转换速度，因此请仅在确实必要时使用此选项。

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### 另请参见

* 类 [UnifiedSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)