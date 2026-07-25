---
title: "MCRElement"
linktitle: "MCRElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中的标记内容引用对象。"
type: docs
weight: 80
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.MCRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.MCRElement

```
public final class MCRElement extends Element
```

表示逻辑结构中的标记内容引用对象。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Handler](#Handler) |  |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MCRElement](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getMCID](#getMCID--) | 获取标记内容引用对象的 MCID。 |
| [getPage](#getPage--) | 获取页面实例 |
| [preSave](#preSave--) |  |
| [setNewMCID](#setNewMCID-int-) | 获取 MCID 值 |
| [setPage](#setPage-com.aspose.pdf.Page-) | 设置页面实例 |
| [tag](#tag-com.aspose.pdf.Annotation-) | 将结构元素绑定到 Annotation。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 将结构元素绑定到 Artifact。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 将结构元素绑定到内容流 BDC 运算符。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 将结构元素绑定到内容流 XForm。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 将结构元素绑定到 XImage。 |
| [toString](#toString--) | 返回表示当前对象的字符串。 |

### Handler {#Handler}
```
public com.aspose.pdf.tagged.helpers.logicalstructure.MCRElementHandler Handler
```



### MCRElement {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
构造函数

### getMCID {#getMCID--}
```
public final int getMCID()
```

获取标记内容引用对象的 MCID。

**Returns:**
标记内容引用对象的 MCID。

### getPage {#getPage--}
```
public final Page getPage()
```

获取页面实例

**Returns:**
页面实例

### preSave {#preSave--}
```
public void preSave()
```



### setNewMCID {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```

获取 MCID 值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | MCID 值 |

### setPage {#setPage-com.aspose.pdf.Page-}
设置页面实例

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
