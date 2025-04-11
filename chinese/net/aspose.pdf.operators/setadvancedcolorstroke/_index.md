---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColorStroke 类。表示 SCN 操作符设置颜色以进行描边操作
type: docs
weight: 7570
url: /zh/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke class

表示 SCN 操作符（设置描边操作的颜色）。

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | 初始化操作符。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | SCN 操作符的构造函数 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | SCN 操作符的构造函数。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | SCN 操作符的构造函数。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | SCN 操作符的构造函数。 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | SCN 操作符的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 获取颜色的红色分量 |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | 获取 CMYK 颜色的青色分量。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色分量数组。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 获取颜色的绿色分量 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色分量。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | 获取 CMYK 颜色的黑色分量。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | 获取 CMYK 颜色的品红色分量。 |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | 获取图案名称。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 获取颜色的红色分量 |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | 获取 CMYK 颜色的黄色分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另请参阅

* class [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)