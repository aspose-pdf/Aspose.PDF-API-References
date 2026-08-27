---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中元素的基类。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

表示逻辑结构中元素的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 将 {@code /Aspose.Pdf.LogicalStructure.Element} 追加到子集合中。 |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 将 {@code /Aspose.Pdf.LogicalStructure.Element} 追加到子集合中。 |
| [clearChilds](#clearChilds--) | 清除所有子项。 |
| [findElements](#findElements-java.lang.Class-) | 查找给定类型的元素 |
| [findElements](#findElements-java.lang.Class-boolean-) | 查找给定类型的元素 |
| [getChildElements](#getChildElements--) | 获取 {@code Element} 对象的子集合。 |
| [getElementEngine](#getElementEngine--) | 获取父元素。 |
| [getParentElement](#getParentElement--) | 获取 {@code Element} 对象的父集合。 |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | 内部方法 |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | 在指定索引处将 {@code /Aspose.Pdf.LogicalStructure.Element} 插入到子集合中。 |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | 在指定索引处将 {@code /Aspose.Pdf.LogicalStructure.Element} 插入到子集合中。 |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | 在此处移除子节点。 |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | 将结构元素绑定到 Annotation。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 将结构元素绑定到 Artifact。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 将结构元素绑定到内容流 BDC 运算符。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 将结构元素绑定到内容流 XForm。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 将结构元素绑定到 XImage。 |
| [toString](#toString--) | 返回表示当前对象的字符串。 |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
将 {@code /Aspose.Pdf.LogicalStructure.Element} 追加到子集合中。

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
将 {@code /Aspose.Pdf.LogicalStructure.Element} 追加到子集合中。

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

清除所有子项。

### findElements {#findElements-java.lang.Class-}
查找给定类型的元素

### findElements {#findElements-java.lang.Class-boolean-}
查找给定类型的元素

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

获取 {@code Element} 对象的子集合。

**Returns:**
值：{@code Element} 对象的子集合。

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

获取父元素。

**Returns:**
值：父元素。

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

获取 {@code Element} 对象的父集合。

**Returns:**
值：{@code Element} 对象的父集合。

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

内部方法

**Returns:**
内部元素

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
在指定索引处将 {@code /Aspose.Pdf.LogicalStructure.Element} 插入到子集合中。

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
在指定索引处将 {@code /Aspose.Pdf.LogicalStructure.Element} 插入到子集合中。

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

在此处移除子节点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 子元素索引。 |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
将结构元素绑定到 Annotation。

### tag {#tag-com.aspose.pdf.Artifact-}
将结构元素绑定到 Artifact。

### tag {#tag-com.aspose.pdf.operators.BDC-}
将结构元素绑定到内容流 BDC 运算符。

### tag {#tag-com.aspose.pdf.XForm-}
将结构元素绑定到内容流 XForm。

### tag {#tag-com.aspose.pdf.XImage-}
将结构元素绑定到 XImage。

### toString {#toString--}
```
public String toString()
```

返回表示当前对象的字符串。

**Returns:**
表示当前对象的字符串。
