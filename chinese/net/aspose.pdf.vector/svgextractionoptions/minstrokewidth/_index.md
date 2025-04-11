---
title: SvgExtractionOptions.MinStrokeWidth
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractionOptions 属性。获取或设置将在生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，将用此宽度替换。默认值为 0.5
type: docs
weight: 60
url: /zh/net/aspose.pdf.vector/svgextractionoptions/minstrokewidth/
---
## SvgExtractionOptions.MinStrokeWidth 属性

获取或设置将在生成的 SVG 中使用的最小笔画宽度。如果 PDF 使用更细的笔画宽度，将用此宽度替换。默认值为 0.5。

```csharp
public double MinStrokeWidth { get; set; }
```

## 备注

该值以转换后的 PDF 页面用户空间单位表示。默认情况下，1 个用户空间单位为 1/72 英寸（0.35 毫米），但这可以被 PDF 文档覆盖。变换可能会影响生成的 SVG 中的实际最小宽度。

### 另请参阅

* 类 [SvgExtractionOptions](../)
* 命名空间 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* 程序集 [Aspose.PDF](../../../)