---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示页面结构对象（如章节和段落）的吸收器对象。执行对文本章节和段落的搜索并提供访问。"
type: docs
weight: 3470
url: /zh/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> 表示页面结构对象（如章节和段落）的吸收器对象。执行对章节和段落文本的搜索，并提供对描述文本坐标空间的矩形和多边形的访问。还执行文本片段搜索，并通过按结构元素分组的 {@code TextFragments} 集合提供对搜索结果的访问。 </p> 示例演示如何在第一个 PDF 文档页面上找到每个段落的第一个文本片段并高亮显示它。 <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> 当搜索完成后，{@code ParagraphAbsorber.PageMarkups} 集合将包含表示页面结构的 {@code PageMarkup} 对象，这些对象由 {@code MarkupSection} 和 {@code MarkupParagraph} 的集合组成。{@code TextFragment} 对象提供对搜索到的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | 初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。 |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> 初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。 </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | 初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。 |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | 初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | 获取已吸收的 {@code PageMarkup} 集合。 |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | 获取 ParagraphAbsorberOptions。 |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> 获取或设置一个值，用于指示对结构更细元素的顺序搜索将执行多少次。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 </p><hr> 增加此值可能会导致性能略有下降，但搜索结果没有可见变化。减少此值可能导致章节中段落的判定不正确。如果您不只想获取页面结构的“粗略”元素，我们不建议将值设定低于默认值。 |
| [getTextReplaceOptions](#getTextReplaceOptions--) | 获取或设置 TextReplaceOptions。 |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | 获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。 |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | 获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。 |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | 设置 ParagraphAbsorberOptions。 |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> 获取或设置一个值，用于指示对结构更细元素的顺序搜索将执行多少次。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 </p><hr> 增加此值可能会导致性能略有下降，但搜索结果没有可见变化。减少此值可能导致章节中段落的判定不正确。如果您不只想获取页面结构的“粗略”元素，我们不建议将值设定低于默认值。 |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | 获取或设置 TextReplaceOptions。 |
| [visit](#visit-com.aspose.pdf.Document-) | 在指定的 {@link Document} 上执行章节和段落的搜索。 |
| [visit](#visit-com.aspose.pdf.Page-) | 在指定的 {@code Page} 上执行搜索。 |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> 初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sectionsSearchDepth |  | 将要执行的对结构更细元素的顺序搜索次数。 <hr> 有关该参数的更多提示，请参阅 {@code ParagraphAbsorber.SectionsSearchDepth} 属性。 <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
初始化一个新的 {@code ParagraphAbsorber} 实例，该实例执行文档或页面的章节/段落搜索。

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

获取已吸收的 {@code PageMarkup} 集合。

**Returns:**
PageMarkup 实例列表

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

获取 ParagraphAbsorberOptions。

**Returns:**
ParagraphAbsorberOptions 实例

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> 获取或设置一个值，用于指示对结构更细元素的顺序搜索将执行多少次。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 </p><hr> 增加此值可能会导致性能略有下降，但搜索结果没有可见变化。减少此值可能导致章节中段落的判定不正确。如果您不只想获取页面结构的“粗略”元素，我们不建议将值设定低于默认值。

**Returns:**
int 值

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

获取或设置 TextReplaceOptions。

**Returns:**
TextReplaceOptions 实例

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。

**Returns:**
布尔值

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
设置 ParagraphAbsorberOptions。

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> 获取或设置一个值，用于指示对结构更细元素的顺序搜索将执行多少次。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 </p><hr> 增加此值可能会导致性能略有下降，但搜索结果没有可见变化。减少此值可能导致章节中段落的判定不正确。如果您不只想获取页面结构的“粗略”元素，我们不建议将值设定低于默认值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
获取或设置 TextReplaceOptions。

### visit {#visit-com.aspose.pdf.Document-}
在指定的 {@link Document} 上执行章节和段落的搜索。

### visit {#visit-com.aspose.pdf.Page-}
在指定的 {@code Page} 上执行搜索。
