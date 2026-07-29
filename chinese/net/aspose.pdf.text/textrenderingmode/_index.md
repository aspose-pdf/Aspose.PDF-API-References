---
title: "枚举 TextRenderingMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextRenderingMode 枚举。文本渲染模式 Tmode 决定显示文本时是对字形轮廓进行描边、填充、用作裁剪边界，还是这三者的某种组合。"
type: docs
weight: 11180
url: /zh/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enumeration

文本渲染模式 Tmode 决定显示文本时是否会对字形轮廓进行描边、填充、用作裁剪边界，或上述三者的组合。

```csharp
public enum TextRenderingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| FillText | `0` | 填充文本。 |
| StrokeText | `1` | 描边文本。 |
| FillThenStrokeText | `2` | 先填充后描边文本。 |
| Invisible | `3` | 既不填充也不描边文本（不可见）。 |
| FillTextAndAddPathToClipping | `4` | 填充文本并将其添加到路径用于裁剪（参见 9.3.6，\"Text Rendering Mode,\"）。 |
| StrokeTextAndAddPathToClipping | `5` | 描边文本并将其添加到路径用于裁剪。 |
| FillThenStrokeTextAndAddPathToClipping | `6` | 先填充后描边文本并将其添加到路径用于裁剪。 |
| AddPathToClipping | `7` | 将文本添加到路径用于裁剪。 |

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


