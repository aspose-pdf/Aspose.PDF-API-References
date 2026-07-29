---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "PDF 文档页面的集合。"
type: docs
weight: 3340
url: /zh/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

PDF 文档页面的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 {@code AnnotationSelector} 访问者对象，该对象提供处理注释的功能。 |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 接受 {@code ImagePlacementAbsorber} 访问者对象，该对象提供处理图像放置对象的功能。 |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | 接受 {@code TextAbsorber} 访问者对象，该对象提供处理文本对象的功能。 |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | 接受 {@code TextFragmentAbsorber} 访问者对象，该对象提供处理文本对象的功能。 |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | 向集合中添加页面。 |
| [add](#add--) | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [add](#add-java.lang.Iterable-) | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [add](#add-java.util.List-) | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [add](#add-com.aspose.pdf.Page-) | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [add](#add-com.aspose.pdf.Page:A-) | 添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [beginUpdate](#beginUpdate--) | 当组更改开始时进行更新。 |
| [clear](#clear--) | 清除页面集合。 |
| [contains](#contains-com.aspose.pdf.Page-) | 确定此实例是否包含该对象。 |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | 将页面复制到文档中。 |
| [delete](#delete--) | 从集合中删除所有页面。 |
| [delete](#delete-int-) | 删除指定的页面。 |
| [delete](#delete-java.lang.Integer:A-) | 从集合中删除所有页面。 |
| [endUpdate](#endUpdate--) | 当组更改完成时进行更新。 |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | 移除页面上的所有字段，并用其值替代。 |
| [freeMemory](#freeMemory--) | 清除缓存数据 |
| [get_Item](#get_Item-int-) | 按索引获取页面。 |
| [getSyncRoot](#getSyncRoot--) | 获取集合的同步对象。 |
| [getUnrestricted](#getUnrestricted-int-) | 按索引返回页面。 {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> 返回指定页面的索引。 </p> |
| [insert](#insert-int-) | 在指定位置向集合中插入一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。 |
| [insert](#insert-int-java.lang.Iterable-) | 将集合中的页面插入到文档中。 |
| [insert](#insert-int-java.util.List-) | 将集合中的页面插入到文档中。 |
| [insert](#insert-int-com.aspose.pdf.Page-) | 在指定位置将页面插入页面集合。 |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | 将数组中的页面插入文档。 |
| [isEmpty](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否只读的值。始终返回 false。 |
| [isSynchronized](#isSynchronized--) | 返回对象已同步为 true。 |
| [iterator](#iterator--) | 返回页面的枚举器。 |
| [remove](#remove-com.aspose.pdf.Page-) | 删除指定的项，抛出异常。 |
| [size](#size--) | 获取文档中页面的计数。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受 {@code AnnotationSelector} 访问者对象，该对象提供处理注释的功能。

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
接受 {@code ImagePlacementAbsorber} 访问者对象，该对象提供处理图像放置对象的功能。

### accept {#accept-com.aspose.pdf.TextAbsorber-}
接受 {@code TextAbsorber} 访问者对象，该对象提供处理文本对象的功能。

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
接受 {@code TextFragmentAbsorber} 访问者对象，该对象提供处理文本对象的功能。

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
向集合中添加页面。

### add {#add--}
```
public Page add()
```

添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Returns:**
已添加页面。

### add {#add-java.lang.Iterable-}
添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Returns:**
已添加页面。

### add {#add-java.util.List-}
添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Returns:**
已添加页面。

### add {#add-com.aspose.pdf.Page-}
添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Returns:**
已添加页面。

### add {#add-com.aspose.pdf.Page:A-}
添加一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Returns:**
已添加页面。

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

当组更改开始时进行更新。

### clear {#clear--}
```
public void clear()
```

清除页面集合。

### contains {#contains-com.aspose.pdf.Page-}
确定此实例是否包含该对象。

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
将页面复制到文档中。

### delete {#delete--}
```
public void delete()
```

从集合中删除所有页面。

### delete {#delete-int-}
```
public void delete(int index)
```

删除指定的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 将被删除的页面编号。页面编号从 1 开始。 |

### delete {#delete-java.lang.Integer:A-}
从集合中删除所有页面。

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

当组更改完成时进行更新。

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

移除页面上的所有字段，并用其值替代。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

清除缓存数据

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

按索引获取页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 页面索引。 |

**Returns:**
已检索的页面。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取集合的同步对象。

**Returns:**
用于同步的对象

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

按索引返回页面。 {@code Page}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 请求页面的索引。页面从 1 编号。 |

**Returns:**
请求的页面

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> 返回指定页面的索引。 </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

在指定位置向集合中插入一个空白页面。如果文档已经包含尺寸不同的页面，将选择出现频率最高的页面尺寸。若只有两种不同的页面，则使用第一页的尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 新页面的位置。 |

**Returns:**
已插入的页面。

### insert {#insert-int-java.lang.Iterable-}
将集合中的页面插入到文档中。

### insert {#insert-int-java.util.List-}
将集合中的页面插入到文档中。

### insert {#insert-int-com.aspose.pdf.Page-}
在指定位置将页面插入页面集合。

### insert {#insert-int-com.aspose.pdf.Page:A-}
将数组中的页面插入文档。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

如果集合为空，则返回 TRUE。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否只读的值。始终返回 false。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

返回对象已同步为 true。

**Returns:**
布尔值

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

返回页面的枚举器。

**Returns:**
页面的枚举器

### remove {#remove-com.aspose.pdf.Page-}
删除指定的项，抛出异常。

### size {#size--}
```
public int size()
```

获取文档中页面的计数。

**Returns:**
int 值
