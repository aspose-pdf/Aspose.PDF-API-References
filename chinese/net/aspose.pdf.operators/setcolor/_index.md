---
title: "类 SetColor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Operators.SetColor 类。表示用于 sc 操作符设置非描边操作颜色的类"
type: docs
weight: 7770
url: /zh/net/aspose.pdf.operators/setcolor/
---
## SetColor class

表示 sc 运算符的类（为非描边操作设置颜色）。

```csharp
public class SetColor : BasicSetColorOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SetColor](setcolor/#constructor)() | 初始化操作符。 |
| [SetColor](setcolor/#constructor_1)(double) | 为描边操作符在 DeviceGray、CalGray 和 Indexed 颜色空间设置颜色。 |
| [SetColor](setcolor/#constructor_4)(double[]) | 构造函数，允许指定颜色分量。 |
| [SetColor](setcolor/#constructor_2)(double, double, double) | 为描边操作符在 DeviceRGB、CalRGB 和 Lab 颜色空间设置颜色 |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | 为非描边操作符设置 CMYK 颜色空间的颜色 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | 获取或设置蓝色分量。 |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | 获取或设置青色分量。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色分量数组。 |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | 获取或设置绿色分量。 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色分量。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | 获取或设置黑色分量。 |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | 获取或设置品红分量。 |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | 获取或设置红色分量。 |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | 获取或设置黄色分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | 返回颜色的字符串表示形式。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另请参见

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


