---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextRenderingMode 枚举。文本渲染模式 Tmode 决定显示文本是否会导致字形轮廓被描边、填充、用作剪裁边界或三者的某种组合。
type: docs
weight: 11000
url: /zh/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode 枚举

文本渲染模式 Tmode 决定显示文本是否会导致字形轮廓被描边、填充、用作剪裁边界或三者的某种组合。

```csharp
public enum TextRenderingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| FillText | `0` | 填充文本。 |
| StrokeText | `1` | 描边文本。 |
| FillThenStrokeText | `2` | 先填充，然后描边文本。 |
| Invisible | `3` | 既不填充也不描边文本（不可见）。 |
| FillTextAndAddPathToClipping | `4` | 填充文本并添加到剪裁路径中（见 9.3.6，“文本渲染模式”）。 |
| StrokeTextAndAddPathToClipping | `5` | 描边文本并添加到剪裁路径中。 |
| FillThenStrokeTextAndAddPathToClipping | `6` | 先填充，然后描边文本并添加到剪裁路径中。 |
| AddPathToClipping | `7` | 将文本添加到剪裁路径中。 |

### 另见

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)