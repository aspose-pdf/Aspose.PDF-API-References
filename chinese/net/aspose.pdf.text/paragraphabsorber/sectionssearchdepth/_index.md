---
title: SectionsSearchDepth
second_title: Aspose.PDF for .NET API 参考
description: 获取或设置值该值指示将执行多少次顺序搜索更精细的结构元素 默认搜索深度为 3 这意味着对水平划分的部分标题段落等进行三次搜索对垂直划分进行三次搜索那些列.
type: docs
weight: 40
url: /zh/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

获取或设置值，该值指示将执行多少次顺序搜索更精细的结构元素。 默认搜索深度为 3。 这意味着对水平划分的部分（标题、段落等）进行三次搜索，对垂直划分进行三次搜索那些（列）.

```csharp
public int SectionsSearchDepth { get; set; }
```

### 评论

增大此值可能会导致性能轻微下降，搜索结果没有明显变化。 减小此值可能会导致部分中的段落确定不正确。 如果您不这样做，我们不建议将值设置为小于默认值希望只获得页面结构的“粗略”元素。

### 也可以看看

* class [ParagraphAbsorber](../../paragraphabsorber)
* 命名空间 [Aspose.Pdf.Text](../../paragraphabsorber)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
