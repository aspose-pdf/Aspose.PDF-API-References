---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin 枚举。线条连接样式应指定在描边路径的角落使用的形状
type: docs
weight: 7450
url: /zh/net/aspose.pdf.operators/linejoin/
---
## LineJoin 枚举

线条连接样式应指定在描边路径的角落使用的形状。

```csharp
public enum LineJoin
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| MiterJoin | `0` | 尖角连接。两个段的外边缘应延伸，直到它们在一个角度相遇，如同画框一样。如果段以过于尖锐的角度相遇，正如由尖角限制参数定义的（见 8.4.3.5，“尖角限制”），则应使用斜角连接。 |
| RoundJoin | `1` | 圆角连接。应在两个段相遇的点周围绘制一个直径等于线宽的圆弧，连接两个段的外边缘。这个扇形图形应被填充，形成一个圆角。 |
| BevelJoin | `2` | 斜角连接。两个段应以平头封闭（见 8.4.3.3，“线条封闭样式”）结束，段末端之外的缺口应用三角形填充。 |

### 另见

* 命名空间 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 程序集 [Aspose.PDF](../../)