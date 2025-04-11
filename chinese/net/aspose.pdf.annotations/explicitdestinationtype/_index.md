---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ExplicitDestinationType 枚举。枚举显式目标的类型
type: docs
weight: 1690
url: /zh/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType 枚举

枚举显式目标的类型。

```csharp
public enum ExplicitDestinationType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| XYZ | `0` | 显示页面，坐标（左，上）定位在窗口的左上角，页面内容按缩放因子放大。任何参数 left、top 或 zoom 的空值指定该参数的当前值保持不变。缩放值为 0 的含义与空值相同。 |
| Fit | `1` | 显示页面，内容放大到刚好足以使整个页面在窗口中水平和垂直适配。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将页面居中。 |
| FitH | `2` | 显示页面，垂直坐标 top 定位在窗口的顶部边缘，页面内容放大到刚好足以使整个页面的宽度在窗口中适配。top 的空值指定该参数的当前值保持不变。 |
| FitV | `3` | 显示页面，水平坐标 left 定位在窗口的左边缘，页面内容放大到刚好足以使整个页面的高度在窗口中适配。left 的空值指定该参数的当前值保持不变。 |
| FitR | `4` | 显示页面，内容放大到刚好足以使由坐标 left、bottom、right 和 top 指定的矩形在窗口中水平和垂直完全适配。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将矩形居中。任何参数的空值可能导致不可预测的行为。 |
| FitB | `5` | 显示页面，内容放大到刚好足以使其边界框在窗口中水平和垂直完全适配。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将边界框居中。 |
| FitBH | `6` | 显示页面，垂直坐标 top 定位在窗口的顶部边缘，页面内容放大到刚好足以使其边界框的整个宽度在窗口中适配。top 的空值指定该参数的当前值保持不变。 |
| FitBV | `7` | 显示页面，水平坐标 left 定位在窗口的左边缘，页面内容放大到刚好足以使其边界框的整个高度在窗口中适配。left 的空值指定该参数的当前值保持不变。 |

### 另请参见

* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 程序集 [Aspose.PDF](../../)