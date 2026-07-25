---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个段落。"
type: docs
weight: 2880
url: /zh/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

表示一个段落。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | 段落续页的页码列表。如果段落在同一页的下一列继续，则该列表将匹配段落开始的页码。 |
| [getFragments](#getFragments--) | <p> 段落中非空的 {@code TextFragment} 对象集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。 |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> 段落的行。每行由文本片段列表表示。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。 |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | 描述段落的多边形的点。起始点是段落的左下角。后续点按逆时针顺序排列。 |
| [getSecondaryPoints](#getSecondaryPoints--) | 描述段落续行的次级多边形的点。如果段落在下一列或页面继续，则该值不为 null。起始点是段落的左下角。后续点按逆时针顺序排列。 |
| [getText](#getText--) | 获取 {@code MarkupParagraph} 对象表示的 {@code string} 文本对象。 |
| [setText](#setText-java.lang.String-) | 获取或设置段落文本。 |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

段落续页的页码列表。如果段落在同一页的下一列继续，则该列表将匹配段落开始的页码。

**Returns:**
整数列表

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> 段落中非空的 {@code TextFragment} 对象集合。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。

**Returns:**
TextFragment 实例列表

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> 段落的行。每行由文本片段列表表示。 </p><hr> {@code TextFragment} 对象提供对搜索出现的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。

**Returns:**
TextFragment 实例列表

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

描述段落的多边形的点。起始点是段落的左下角。后续点按逆时针顺序排列。

**Returns:**
Point 实例数组

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

描述段落续行的次级多边形的点。如果段落在下一列或页面继续，则该值不为 null。起始点是段落的左下角。后续点按逆时针顺序排列。

**Returns:**
Point[] 列表

### getText {#getText--}
```
public String getText()
```

获取 {@code MarkupParagraph} 对象表示的 {@code string} 文本对象。

**Returns:**
字符串值

### setText {#setText-java.lang.String-}
获取或设置段落文本。
