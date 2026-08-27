---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Aspose.PDF for Java API 参考"
description: "页面标记由 {@code MarkupSection} 和 {@code MarkupParagraph} 的集合表示。"
type: docs
weight: 3420
url: /zh/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

页面标记由 {@code MarkupSection} 和 {@code MarkupParagraph} 的集合表示。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumber](#getNumber--) | 获取处理后的页码。 |
| [getParagraphs](#getParagraphs--) | 获取页面上找到的 {@code MarkupParagraph} 集合。 |
| [getRectangle](#getRectangle--) | 获取处理后的页面矩形。 |
| [getSections](#getSections--) | 获取页面上找到的 {@code MarkupSection} 集合。 |
| [getTextFragments](#getTextFragments--) | <p> 获取页面上找到的 {@code TextFragment} 集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。 |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | 获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。 |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | 获取或设置指示是否将下一节的起始文本行视为前一节最后一个段落的延续的值。 |

### getNumber {#getNumber--}
```
public int getNumber()
```

获取处理后的页码。

**Returns:**
int 值

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

获取页面上找到的 {@code MarkupParagraph} 集合。

**Returns:**
MarkupParagraph 实例列表

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取处理后的页面矩形。

**Returns:**
Rectangle 对象

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

获取页面上找到的 {@code MarkupSection} 集合。

**Returns:**
MarkupSection 实例列表

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> 获取页面上找到的 {@code TextFragment} 集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。

**Returns:**
TextFragment 实例列表

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
