---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator 类。所有用于输出文本的操作符的抽象基类（Tj, TJ 等）。
type: docs
weight: 7920
url: /zh/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

所有用于输出文本的操作符的抽象基类（Tj, TJ 等）。

```csharp
public class TextShowOperator : TextOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | 初始化 TextShowOperator。 |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | 初始化允许传递 TextProperties 的 TextShowOperator。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | 获取操作符在页面上输出的文本。 |

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