---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "文本标记注释的抽象基类。"
type: docs
weight: 5180
url: /zh/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

文本标记注释的抽象基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新 QuadPoints。 |
| [getMarkedText](#getMarkedText--) | 获取标记注释下的文本，返回字符串。 |
| [getMarkedTextFragments](#getMarkedTextFragments--) | 获取标记注释下的文本，返回 {@code TextFragmentCollection}。 |
| [getQuadPoints](#getQuadPoints--) | 获取一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。 |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | 设置一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。 |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换更新 QuadPoints。

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

获取标记注释下的文本，返回字符串。

**Returns:**
包含标记注释下文本的字符串。

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

获取标记注释下的文本，返回 {@code TextFragmentCollection}。

**Returns:**
{@code TextFragmentCollection} 包含标记注释下的 {@code TextFragment}。

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

获取一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。

**Returns:**
Point 值数组

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
设置一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。
