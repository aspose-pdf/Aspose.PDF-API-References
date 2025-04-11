---
title: Class SetGlyphsPositionShowText
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetGlyphsPositionShowText 类。表示带有字形定位的 TJ 操作符显示文本的类
type: docs
weight: 7710
url: /zh/net/aspose.pdf.operators/setglyphspositionshowtext/
---
## SetGlyphsPositionShowText class

表示 TJ 操作符（带有字形定位的显示文本）。

```csharp
public class SetGlyphsPositionShowText : TextShowOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [SetGlyphsPositionShowText](setglyphspositionshowtext/)(IEnumerable&lt;GlyphPosition&gt;) | TJ 操作符的构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [GlyphPositions](../../aspose.pdf.operators/setglyphspositionshowtext/glyphpositions/) { get; } | 返回字形的位置。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 页面操作符列表中的操作符索引。 |
| override [Text](../../aspose.pdf.operators/setglyphspositionshowtext/text/) { get; } | 从操作符参数获取文本（忽略字形定位）。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setglyphspositionshowtext/accept/)(IOperatorSelector) | 接受访问者对象以处理操作符。 |
| override [ToString](../../aspose.pdf.operators/setglyphspositionshowtext/tostring/)() | 返回操作符的文本表示。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 将此实例与给定对象进行比较。 |

### See Also

* class [TextShowOperator](../textshowoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)