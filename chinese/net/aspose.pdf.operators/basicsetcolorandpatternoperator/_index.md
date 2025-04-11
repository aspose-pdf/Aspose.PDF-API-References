---
title: Class BasicSetColorAndPatternOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.BasicSetColorAndPatternOperator 类。所有设置颜色操作符的基础操作符
type: docs
weight: 7150
url: /zh/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## BasicSetColorAndPatternOperator class

所有设置颜色操作符的基础操作符。

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## Properties

| Name | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 获取颜色的红色分量 |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | 获取CMYK颜色的青色分量。 |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 获取颜色分量数组。 |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 获取颜色的绿色分量 |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 获取灰色的黑色分量。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | 获取CMYK颜色的黑色分量。 |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | 获取CMYK颜色的品红色分量。 |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | 获取图案名称。 |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 获取颜色的红色分量 |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | 获取CMYK颜色的黄色分量。 |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | 接受提供操作符处理的访问者 IOperatorSelector。 |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | 返回操作符指定的颜色。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### See Also

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)