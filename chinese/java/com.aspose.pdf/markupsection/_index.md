---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示标记章节——页面上包含文本的矩形区域，可在视觉上与其他文本块区分开来。"
type: docs
weight: 2890
url: /zh/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

表示标记章节——页面上包含文本的矩形区域，可在视觉上与其他文本块区分开来。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFragments](#getFragments--) | <p> 包含在该节内的非空 {@code TextFragment} 对象的集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本以及更改文本状态（字体、字号、颜色等）。 |
| [getParagraphs](#getParagraphs--) | 该节内的 {@code MarkupParagraph} 对象的集合。 |
| [getRectangle](#getRectangle--) | 节矩形 |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> 包含在该节内的非空 {@code TextFragment} 对象的集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本以及更改文本状态（字体、字号、颜色等）。

**Returns:**
TextFragment 实例列表

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

该节内的 {@code MarkupParagraph} 对象的集合。

**Returns:**
MarkupParagraph 实例列表

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

节矩形

**Returns:**
Rectangle 实例
