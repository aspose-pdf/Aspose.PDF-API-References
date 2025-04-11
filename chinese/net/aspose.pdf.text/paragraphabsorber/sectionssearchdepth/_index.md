---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: ParagraphAbsorber 属性。获取或设置指示将执行多少次顺序搜索以查找更细的结构元素的值。默认搜索深度为 3。这意味着对水平划分的部分（标题、段落等）进行三次搜索，对垂直划分的部分（列）进行三次搜索。
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth 属性

获取或设置指示将执行多少次顺序搜索以查找更细的结构元素的值。默认搜索深度为 3。这意味着对水平划分的部分（标题、段落等）进行三次搜索，对垂直划分的部分（列）进行三次搜索。

```csharp
public int SectionsSearchDepth { get; set; }
```

## 备注

增加此值可能会导致性能轻微下降，而搜索结果没有明显变化。减少此值可能会导致在部分中段落的错误确定。如果您不希望仅获取页面结构的“粗略”元素，我们不建议将值设置为低于默认值。

### 另请参见

* 类 [ParagraphAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)