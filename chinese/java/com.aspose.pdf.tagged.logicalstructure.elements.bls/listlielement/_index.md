---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示列表逻辑结构中的 LI 结构元素。"
type: docs
weight: 110
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

表示列表逻辑结构中的 LI 结构元素。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 在此目录项（TOCI）元素中添加对指定 {@link StructureElement} 的引用。通常在 {@code ListLIElement} 作为嵌套目录的标题时使用。 |
| [getGetElement](#getGetElement--) | 获取表示此 TOCI 结构的底层 PDF 元素。 |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
在此目录项（TOCI）元素中添加对指定 {@link StructureElement} 的引用。通常在 {@code ListLIElement} 作为嵌套目录的标题时使用。

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

获取表示此 TOCI 结构的底层 PDF 元素。

**Returns:**
形成此目录条目结构表示的 Element。

### preSave {#preSave--}
```
public void preSave()
```
