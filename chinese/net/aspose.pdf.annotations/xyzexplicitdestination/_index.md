---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XYZExplicitDestination 类。表示显式目标，该目标显示页面，坐标 (left, top) 位于窗口的左上角，页面内容按缩放因子放大。对于任何参数 left、top 或 zoom 的空值指定该参数的当前值保持不变。缩放值为 0 的含义与空值相同。
type: docs
weight: 2730
url: /zh/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

表示显式目标，该目标显示页面，坐标 (left, top) 位于窗口的左上角，页面内容按缩放因子放大。对于任何参数 left、top 或 zoom 的空值指定该参数的当前值保持不变。缩放值为 0 的含义与空值相同。

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | 创建远程显式目标。 |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | 创建本地显式目标。 |

## Properties

| Name | Description |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | 获取窗口左上角的左侧水平坐标。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 获取目标页面对象 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 获取目标页面编号 |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | 获取窗口左上角的顶部垂直坐标。 |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | 获取缩放因子。 |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | 创建目标到指定页面位置，必要时考虑页面旋转。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | 创建目标到指定页面。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | 创建目标到指定页面的左上角。 |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | 将对象状态转换为字符串值。示例：“1 XYZ 100 200 3”。 |

## Examples

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)