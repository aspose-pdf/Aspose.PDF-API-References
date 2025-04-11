---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operator 类。表示操作符的抽象类
type: docs
weight: 7070
url: /zh/net/aspose.pdf/operator/
---
## 操作符类

表示操作符的抽象类。

```csharp
public abstract class Operator
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | 接受提供操作符处理的访问者 IOperatorSelector。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | 确定操作符是否为负责文本输出的操作符（Tj, TJ 等）。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)