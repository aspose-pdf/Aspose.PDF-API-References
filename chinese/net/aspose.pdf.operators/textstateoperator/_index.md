---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextStateOperator 类。用于改变当前文本状态的操作符的抽象基类（Tc, Tf, TL 等）。
type: docs
weight: 7930
url: /zh/net/aspose.pdf.operators/textstateoperator/
---
## TextStateOperator class

用于改变当前文本状态（Tc, Tf, TL 等）的操作符的抽象基类。

```csharp
public class TextStateOperator : TextOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | 初始化 TextStateOperator。 |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | 初始化 TextStateOperator，允许传递 TextProperties。 |

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

### 另请参阅

* 类 [TextOperator](../textoperator/)
* 命名空间 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 程序集 [Aspose.PDF](../../)