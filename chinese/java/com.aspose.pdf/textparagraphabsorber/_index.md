---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本段落的吸收器对象。执行文本搜索并通过 {@code TextParagraphAbsorber.TextParagraphs} 集合提供对搜索结果的访问。"
type: docs
weight: 5220
url: /zh/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

表示文本段落的吸收器对象。执行文本搜索并通过 {@code TextParagraphAbsorber.TextParagraphs} 集合提供对搜索结果的访问。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> 初始化一个带有矩形集合的 {@code TextParagraphAbsorber} 的新实例。 </p> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRectangles](#getRectangles--) | 获取 {@code TextParagraphAbsorber} 用于在 PDF 文档或页面上搜索文本段落的矩形。 |
| [getTextParagraphs](#getTextParagraphs--) | 获取以 {@code TextParagraph} 对象呈现的搜索匹配项集合。 |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | 设置 {@code TextParagraphAbsorber} 用于在 PDF 文档或页面上搜索文本段落的矩形。 |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | 设置以 {@code TextParagraph} 对象呈现的搜索匹配项集合。 |
| [visit](#visit-com.aspose.pdf.Page-) | 在指定页面上执行搜索。 |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> 初始化一个带有矩形集合的 {@code TextParagraphAbsorber} 的新实例。 </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

获取 {@code TextParagraphAbsorber} 用于在 PDF 文档或页面上搜索文本段落的矩形。

**Returns:**
矩形数组

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

获取以 {@code TextParagraph} 对象呈现的搜索匹配项集合。

**Returns:**
TextParagraphCollection 值

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
设置 {@code TextParagraphAbsorber} 用于在 PDF 文档或页面上搜索文本段落的矩形。

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
设置以 {@code TextParagraph} 对象呈现的搜索匹配项集合。

### visit {#visit-com.aspose.pdf.Page-}
在指定页面上执行搜索。
