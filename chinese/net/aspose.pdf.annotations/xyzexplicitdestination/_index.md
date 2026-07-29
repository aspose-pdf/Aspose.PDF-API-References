---
title: "类 XYZExplicitDestination"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination 类。表示显式目标，它在窗口的左上角显示页面，并将页面内容按 zoom 因子放大。对于参数 left、top 或 zoom 的任何空值，表示保留该参数的当前值不变。zoom 为 0 的值具有与空值相同的含义。"
type: docs
weight: 2830
url: /zh/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

表示显式目标，该目标在窗口左上角显示页面，坐标 (left, top) 位于窗口左上角，并按 zoom 因子放大页面内容。对于参数 left、top 或 zoom 的任意 null 值，表示该参数的当前值保持不变。zoom 为 0 的值具有与 null 值相同的含义。

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | 创建远程显式目标。 |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | 创建本地显式目标。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | 获取窗口左上角的左水平坐标。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 获取目标页面对象 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 获取目标页面编号 |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | 获取窗口左上角的顶部垂直坐标。 |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | 获取 zoom 因子。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | 创建目标到页面的指定位置，必要时考虑页面旋转。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | 创建目标到指定页面。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | 创建目标到指定页面的左上角。 |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | 将对象状态转换为字符串值。例如："1 XYZ 100 200 3"。 |

## 示例

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### 另请参见

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


