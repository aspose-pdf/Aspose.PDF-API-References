---
title: "类 SetColorStroke"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Operators.SetColorStroke 类。类表示 SC 操作符用于为描边颜色操作设置颜色"
type: docs
weight: 7820
url: /zh/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

表示 SC 运算符的类，用于为描边颜色运算符设置颜色。

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | 初始化操作符。 |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | 为描边操作符在 DeviceGray、CalGray 和 Indexed 颜色空间设置颜色。 |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | 允许设置颜色分量的构造函数。 |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | 为描边操作符在 DeviceRGB、CalRGB 和 Lab 颜色空间设置颜色 |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | 为描边操作符在 CMYK 颜色空间设置颜色 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | 获取或设置蓝色分量。 |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | 获取或设置青色分量。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色分量数组。 |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | 获取或设置绿色分量。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色分量。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | 获取或设置黑色分量。 |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | 获取或设置品红分量。 |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | 获取或设置红色分量。 |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | 获取或设置黄色分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另请参见

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


