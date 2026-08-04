---
title: "ExplicitDestinationType"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "显式目标类型的枚举。"
type: docs
weight: 1020
url: /zh/python-net/aspose.pdf.annotations/explicitdestinationtype/
---

## ExplicitDestinationType enumeration

显式目标类型的枚举。

## Members
| Member name | 描述 |
| :- | :- |
| XYZ | 在窗口的左上角显示页面，坐标 (left, top) 位于窗口左上角<br/>            并且页面内容按 zoom 因子放大。任意参数 left、top 或 zoom 为 null 时，表示保留该参数的当前值不变。<br/>            zoom 值为 0 的含义与 null 值相同。 |
| FIT | 将页面显示为内容放大到恰好能够在窗口内完整显示整页，<br/>            水平和垂直方向均适配。若所需的水平和垂直放大系数不同，使用较小的那个，并在另一维度上将页面居中。 |
| FIT_H | 将页面显示为垂直坐标 top 位于窗口顶部边缘，<br/>            并且页面内容放大到恰好能够在窗口内完整显示页面的全部宽度。<br/>            top 为 null 时表示保留该参数的当前值不变。 |
| FIT_V | 将页面显示为水平坐标 left 位于窗口左侧边缘，<br/>            并且页面内容放大到恰好能够在窗口内完整显示页面的全部高度。<br/>            left 为 null 时表示保留该参数的当前值不变。 |
| FIT_R | 将页面显示为内容放大到恰好能够在窗口内水平和垂直方向完整显示由坐标 left、bottom、right、top 指定的矩形。<br/>            若所需的水平和垂直放大系数不同，使用较小的那个，并在另一维度上将矩形居中。任意参数为 null 可能导致不可预期的行为。 |
| FIT_B | 将页面显示为内容放大到恰好能够在窗口内水平和垂直方向完整显示其边界框。<br/>            若所需的水平和垂直放大系数不同，使用较小的那个，并在另一维度上将边界框居中。 |
| FIT_BH | 将页面显示为垂直坐标 top 位于窗口顶部边缘，<br/>            并且页面内容放大到恰好能够在窗口内完整显示其边界框的全部宽度。<br/>            top 为 null 时表示保留该参数的当前值不变。 |
| FIT_BV | 将页面显示为水平坐标 left 位于窗口左侧边缘，<br/>            并且页面内容放大到恰好能够在窗口内完整显示其边界框的全部高度。<br/>            left 为 null 时表示保留该参数的当前值不变。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

