---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash 类。表示 d 操作符设置线条虚线模式的类
type: docs
weight: 7690
url: /zh/net/aspose.pdf.operators/setdash/
---
## SetDash class

表示 d 操作符（设置线条虚线模式）的类。

```csharp
public class SetDash : Operator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetDash](setdash/)(int[], int) | 创建设置虚线模式操作符。 |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | 虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。如果是一个元素数组，则虚线和间隙长度相等。 |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | 虚线相位。在开始描绘路径之前，虚线数组应循环，通过累加虚线和间隙的长度。当累积长度等于虚线相位指定的值时，路径的描绘应开始，并且从那时起虚线数组应循环使用。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | 获取操作符的字符串表示。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### See Also

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)