---
title: "类 BlockTextOperator"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Operators.BlockTextOperator 类。抽象基类用于文本块操作符，即开始和结束文本操作符 BT/ET"
type: docs
weight: 7310
url: /zh/net/aspose.pdf.operators/blocktextoperator/
---
## BlockTextOperator class

文本块操作符的抽象基类，即 Begin 和 End 文本操作符（BT/ET）

```csharp
public class BlockTextOperator : TextOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BlockTextOperator](blocktextoperator/#constructor)() | 初始化操作符。 |
| [BlockTextOperator](blocktextoperator/#constructor_1)(TextProperties) | 初始化接受 TextProperties 的 BlockTextOperator。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 返回操作符及其参数的文本。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### 另请参见

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


