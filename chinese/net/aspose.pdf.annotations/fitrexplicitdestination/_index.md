---
title: "类 FitRExplicitDestination"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.FitRExplicitDestination 类。表示显式目标，显示页面时将其内容放大到恰好适合由左、下、右、上坐标指定的矩形，使其完整地水平和垂直居中显示在窗口中。如果所需的水平和垂直放大因子不同，则使用较小的因子，并在另一维度上将矩形居中。任何参数的 null 值可能导致不可预期的行为。"
type: docs
weight: 1870
url: /zh/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

表示显式目标，该目标显示页面，并将其内容放大到恰好使由 left、bottom、right 和 top 坐标指定的矩形在水平和垂直方向上完全适合窗口。如果所需的水平和垂直放大系数不同，则使用两者中较小的一个，并在另一维度上将矩形居中于窗口。任何参数为 null 值可能导致不可预测的行为。

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | 创建远程显式目标。 |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | 创建本地显式目标。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 获取可见矩形的底部垂直坐标。 |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 获取可见矩形的左侧水平坐标。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 获取目标页面对象 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 获取目标页面编号 |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 获取可见矩形的右侧水平坐标。 |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 获取可见矩形的顶部垂直坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | 将对象状态转换为字符串值。示例：\"1 FitR 100 200 300 400\"。 |

### 另请参见

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


