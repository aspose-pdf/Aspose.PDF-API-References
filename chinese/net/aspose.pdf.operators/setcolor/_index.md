---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor 类。表示用于非描边操作的 sc 操作符设置颜色的类
type: docs
weight: 7630
url: /zh/net/aspose.pdf.operators/setcolor/
---
## SetColor class

表示 sc 操作符（为非描边操作设置颜色）的类。

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetColor](setcolor/#constructor)() | 初始化操作符。 |
| [SetColor](setcolor/#constructor_1)(double) | 为 DeviceGray、CalGray 和 Indexed 颜色空间的描边操作符设置颜色。 |
| [SetColor](setcolor/#constructor_4)(double[]) | 允许指定颜色组件的构造函数。 |
| [SetColor](setcolor/#constructor_2)(double, double, double) | 为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边操作符设置颜色 |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | 为 CMYK 颜色空间的非描边操作符设置颜色 |

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | 获取或设置蓝色组件。 |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | 获取或设置青色组件。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色组件数组。 |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | 获取或设置绿色组件。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色组件。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | 获取或设置黑色组件。 |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | 获取或设置品红色组件。 |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | 获取或设置红色组件。 |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | 获取或设置黄色组件。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | 返回颜色的字符串表示。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)