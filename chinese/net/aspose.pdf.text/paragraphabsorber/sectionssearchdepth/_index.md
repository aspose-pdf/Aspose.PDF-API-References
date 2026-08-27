---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Aspose.PDF for .NET API 参考"
description: "ParagraphAbsorber 属性。获取或设置指示将在结构中更细元素上执行多少次顺序搜索的值。默认搜索深度为 3。这意味着对水平划分的章节、标题、段落等进行三次搜索，对垂直划分的列也进行三次搜索。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

获取或设置指示对结构更细元素进行顺序搜索次数的值。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。

```csharp
public int SectionsSearchDepth { get; set; }
```

## 备注

增加此值可能会导致性能略有下降，但搜索结果没有可见变化。减少此值可能会导致章节中段落的判定不正确。如果您不希望仅获取页面结构的‘rough’元素，我们不建议将该值设置低于默认值。

### 另请参见

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


