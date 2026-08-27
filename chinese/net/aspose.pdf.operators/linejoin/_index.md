---
title: "枚举 LineJoin"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Operators.LineJoin 枚举。线段连接样式应指定在已描边路径的拐角处使用的形状"
type: docs
weight: 7590
url: /zh/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

线段连接样式应指定在描边路径的拐角处使用的形状。

```csharp
public enum LineJoin
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| MiterJoin | `0` | 斜接连接。两个线段的描边外缘应延伸至相交形成角度，类似相框。如果线段以过于尖锐的角度相交（由斜接限制参数定义，参见 8.4.3.5，“Miter Limit”），则改用斜面连接。 |
| RoundJoin | `1` | 圆形连接。将在两个线段相交点周围绘制直径等于线宽的圆弧，以连接两个线段的描边外缘。该扇形图形将被填充，从而形成圆角。 |
| BevelJoin | `2` | 斜面连接。两个线段应使用平帽结束（参见 8.4.3.3，“Line Cap Style”），并将线段末端之外产生的缺口填充为三角形。 |

### 另请参见

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


