---
title: Class SetAdvancedColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColor 类。表示用于非描边操作的 scn 操作符设置颜色的类
type: docs
weight: 7560
url: /zh/net/aspose.pdf.operators/setadvancedcolor/
---
## SetAdvancedColor 类

表示 scn 操作符（为非描边操作设置颜色）。

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | 初始化操作符。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double) | scn 操作符的构造函数。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(string) | scn 操作符的构造函数。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, string) | scn 操作符的构造函数。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(double[], string) | scn 操作符的构造函数。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | scn 操作符的构造函数。 |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double, double, double, double, string) | scn 操作符的构造函数。 |

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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | 获取模式名称。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 获取颜色的红色分量 |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | 获取 CMYK 颜色的黄色分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另见

* 类 [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* 命名空间 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 程序集 [Aspose.PDF](../../)