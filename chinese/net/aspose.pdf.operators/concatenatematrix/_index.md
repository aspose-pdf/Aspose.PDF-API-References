---
title: Class ConcatenateMatrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.ConcatenateMatrix 类。表示将 cm 操作符连接矩阵到当前变换矩阵的类
type: docs
weight: 7230
url: /zh/net/aspose.pdf.operators/concatenatematrix/
---
## ConcatenateMatrix 类

表示 cm 操作符（将矩阵连接到当前变换矩阵）。

```csharp
public class ConcatenateMatrix : Operator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ConcatenateMatrix](concatenatematrix/#constructor)(Matrix) | 通过矩阵初始化操作符。 |
| [ConcatenateMatrix](concatenatematrix/#constructor_1)(double, double, double, double, double, double) | 初始化操作符。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| [Matrix](../../aspose.pdf.operators/concatenatematrix/matrix/) { get; set; } | 操作符的矩阵参数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/concatenatematrix/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [ToString](../../aspose.pdf.operators/concatenatematrix/tostring/)() | 返回操作符的文本表示。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另请参阅

* 类 [Operator](../../aspose.pdf/operator/)
* 命名空间 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 程序集 [Aspose.PDF](../../)