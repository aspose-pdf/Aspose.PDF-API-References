---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke 类。表示 SC 操作符设置描边颜色的操作符
type: docs
weight: 7680
url: /zh/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

表示 SC 操作符设置描边颜色的操作符。

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | 初始化操作符。 |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | 为 DeviceGray、CalGray 和 Indexed 颜色空间的描边操作符设置颜色。 |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | 允许设置颜色组件的构造函数。 |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | 为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边操作符设置颜色 |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | 为 CMYK 颜色空间的描边操作符设置颜色 |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | 获取或设置蓝色组件。 |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | 获取或设置青色组件。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色组件数组。 |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | 获取或设置绿色组件。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色组件。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | 获取或设置黑色组件。 |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | 获取或设置品红色组件。 |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | 获取或设置红色组件。 |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | 获取或设置黄色组件。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)