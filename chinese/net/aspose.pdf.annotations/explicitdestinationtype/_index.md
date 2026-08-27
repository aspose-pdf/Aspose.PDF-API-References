---
title: "枚举 ExplicitDestinationType"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.ExplicitDestinationType 枚举。枚举显式目标的类型"
type: docs
weight: 1780
url: /zh/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

枚举显式目标的类型。

```csharp
public enum ExplicitDestinationType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| XYZ | `0` | 显示页面时，将坐标 (left, top) 定位在窗口的左上角，并按 zoom 因子放大页面内容。对 left、top 或 zoom 任一参数使用 null 值表示该参数的当前值保持不变。zoom 为 0 的值具有与 null 值相同的含义。 |
| Fit | `1` | 显示页面时，将其内容放大到恰好能够在窗口中水平和垂直方向完整显示整页。如果所需的水平和垂直放大因子不同，则使用两者中较小的一个，并在另一维度上将页面居中显示。 |
| FitH | `2` | 显示页面时，将垂直坐标 top 定位在窗口的顶部边缘，并将页面内容放大到恰好能够在窗口中完整显示页面的整个宽度。对 top 使用 null 值表示该参数的当前值保持不变。 |
| FitV | `3` | 显示页面时，将水平坐标 left 定位在窗口的左侧边缘，并将页面内容放大到恰好能够在窗口中完整显示页面的整个高度。对 left 使用 null 值表示该参数的当前值保持不变。 |
| FitR | `4` | 在窗口中水平和垂直方向上，将页面显示为其内容放大到恰好能够完整容纳由坐标 left、bottom、right 和 top 指定的矩形。若所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将矩形居中显示。对任何参数使用 null 值可能导致不可预期的行为。 |
| FitB | `5` | 在窗口中水平和垂直方向上，将页面显示为其内容放大到恰好能够完整容纳其边界框。若所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将边界框居中显示。 |
| FitBH | `6` | 将页面显示为垂直坐标 top 位于窗口的顶部边缘，并将页面内容放大到恰好能够使其边界框的整个宽度容纳在窗口内。对 top 使用 null 值表示保留该参数的当前值不变。 |
| FitBV | `7` | 将页面显示为水平坐标 left 位于窗口的左侧边缘，并将页面内容放大到恰好能够使其边界框的整个高度容纳在窗口内。对 left 使用 null 值表示保留该参数的当前值不变。 |

### 另请参见

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


