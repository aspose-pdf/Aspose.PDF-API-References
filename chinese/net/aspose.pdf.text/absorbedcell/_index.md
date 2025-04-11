---
title: Class AbsorbedCell
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.AbsorbedCell 类。表示页面上存在的表格单元格
type: docs
weight: 10410
url: /zh/net/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell class

表示页面上存在的表格单元格

```csharp
public class AbsorbedCell : IComparable<AbsorbedCell>, ITableElement
```

## Properties

| Name | Description |
| --- | --- |
| [BorderInfo](../../aspose.pdf.text/absorbedcell/borderinfo/) { get; } | 当 FlowEngine.TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格的边框信息。 |
| [ColSpan](../../aspose.pdf.text/absorbedcell/colspan/) { get; } | 当 TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格应跨越的列数。 |
| [Rectangle](../../aspose.pdf.text/absorbedcell/rectangle/) { get; } | 获取描述单元格在页面上位置的矩形 |
| [TextFragments](../../aspose.pdf.text/absorbedcell/textfragments/) { get; } | 获取描述单元格中包含文本的 [`TextFragment`](../textfragment/) 对象的集合 |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.text/absorbedcell/compareto/)(AbsorbedCell) | 将当前的 AbsorbedCell 对象与另一个 AbsorbedCell 对象进行比较，并返回一个整数，指示当前对象在排序顺序中是位于另一个对象之前、之后，还是处于相同位置。 |

### See Also

* interface [ITableElement](../itableelement/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)