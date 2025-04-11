---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FitRExplicitDestination 类。表示明确的目标，该目标显示页面及其内容的放大程度刚好足以适应由左、下、右和顶部坐标指定的矩形，完全在窗口内水平和垂直显示。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将矩形居中。任何参数的空值可能导致不可预测的行为。
type: docs
weight: 1780
url: /zh/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

表示明确的目标，该目标显示页面及其内容的放大程度刚好足以适应由左、下、右和顶部坐标指定的矩形，完全在窗口内水平和垂直显示。如果所需的水平和垂直放大因子不同，则使用两个中的较小者，在另一个维度中将矩形居中。任何参数的空值可能导致不可预测的行为。

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | 创建远程明确目标。 |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | 创建本地明确目标。 |

## Properties

| Name | Description |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 获取可见矩形的底部垂直坐标。 |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 获取可见矩形的左侧水平坐标。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 获取目标页面对象 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 获取目标页面编号 |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 获取可见矩形的右侧水平坐标。 |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 获取可见矩形的顶部垂直坐标。 |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | 将对象状态转换为字符串值。示例：“1 FitR 100 200 300 400”。 |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)