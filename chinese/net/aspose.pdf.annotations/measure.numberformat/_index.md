---
title: Class Measure.NumberFormat
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MeasureNumberFormat class. 数值格式用于测量
type: docs
weight: 2040
url: /zh/net/aspose.pdf.annotations/measure.numberformat/
---
## Measure.NumberFormat class

数值格式用于测量。

```csharp
public class NumberFormat
```

## Constructors

| Name | Description |
| --- | --- |
| [NumberFormat](../../aspose.pdf.annotations/measure.numberformat/.ctor)(Measure) | NumberFormat 类的构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AfterText](../../aspose.pdf.annotations/measure.numberformat/aftertext) { get; set; } | 应该在标签后连接的文本 |
| [BeforeText](../../aspose.pdf.annotations/measure.numberformat/beforetext) { get; set; } | 应该在标签左侧连接的文本。 |
| [ConvresionFactor](../../aspose.pdf.annotations/measure.numberformat/convresionfactor) { get; set; } | 用于将前一个数值格式数组元素的部分单位值乘以以获得此数值格式单位的值的转换因子。 |
| [Denominator](../../aspose.pdf.annotations/measure.numberformat/denominator) { get; set; } | 如果 FractionDisplayment 为 ShowAsFraction，则此值为分数的分母。默认值为 16。 |
| [ForceDenominator](../../aspose.pdf.annotations/measure.numberformat/forcedenominator) { get; set; } | 如果 FractionDisplayment 为 ShowAsFraction，则此值决定分数是否可以被简化。如果值为 true，则分数可能不会被简化。 |
| [FractionDisplayment](../../aspose.pdf.annotations/measure.numberformat/fractiondisplayment) { get; set; } | 分数值的显示方式。 |
| [FractionSeparator](../../aspose.pdf.annotations/measure.numberformat/fractionseparator) { get; set; } | 应该用作显示数值时小数位置的文本。空字符串表示将使用默认值。默认是句点字符。 |
| [Precision](../../aspose.pdf.annotations/measure.numberformat/precision) { get; set; } | 如果 FractionDisplayment 为 ShowAsDecimal，则此值为分数值的精度；它应为 10 的倍数。默认值为 100。 |
| [ThousandsSeparator](../../aspose.pdf.annotations/measure.numberformat/thousandsseparator) { get; set; } | 应该在数值显示的千位之间使用的文本。空字符串表示不应添加任何文本。默认是逗号。 |
| [UnitLabel](../../aspose.pdf.annotations/measure.numberformat/unitlabel) { get; set; } | 指定用于显示单位的标签的文本字符串。 |

### See Also

* class [Measure](../measure/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)