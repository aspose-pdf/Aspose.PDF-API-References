---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档大纲层次结构中的大纲条目。"
type: docs
weight: 3270
url: /zh/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

表示 PDF 文档大纲层次结构中的大纲条目。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | 使用内部引擎大纲条目对象初始化此类的新实例。 |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | 使用根层次结构对象初始化大纲项实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | 向集合中添加大纲项。 |
| [clear](#clear--) | 清除集合中的所有项。 |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。始终抛出 NotImplementedException。 |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | 将大纲条目复制到 System.Array 中，从特定的 System.Array 索引开始。 |
| [delete](#delete--) | 从文档大纲层次结构中删除此大纲项。 |
| [delete](#delete-java.lang.String-) | 从文档大纲层次结构中删除此大纲项。 |
| [get_Item](#get_Item-int-) | 使用索引从集合中获取大纲项。 |
| [getAction](#getAction--) | 获取此大纲项的操作。 |
| [getBold](#getBold--) | 获取此大纲项标题文本的粗体标志 |
| [getColor](#getColor--) | 获取此大纲项标题文本的颜色。 |
| [getDestination](#getDestination--) | 获取此大纲项的目标。 |
| [getEngineDict](#getEngineDict--) | 仅内部使用 |
| [getEngineObj](#getEngineObj--) | 仅内部使用 |
| [getFirst](#getFirst--) | 获取表示大纲层次结构中第一个顶级项的大纲项。 |
| [getItalic](#getItalic--) | 获取此大纲项标题文本的斜体标志 |
| [getLast](#getLast--) | 获取表示大纲层次结构中最后一个顶级项的大纲项。 |
| [getLevel](#getLevel--) | 获取大纲项的层级级别。 |
| [getNext](#getNext--) | 获取表示相对于此项在大纲层次结构中下一个项的大纲项。 |
| [getOpen](#getOpen--) | 获取大纲项的打开状态（true/false）。 |
| [getParent](#getParent--) | 获取此大纲项在大纲层次结构中的父对象。 |
| [getPrev](#getPrev--) | 获取表示相对于此项在大纲层次结构中上一个项的大纲项。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问此集合的对象。 |
| [getTitle](#getTitle--) | 获取此大纲项的标题。 |
| [getVisibleCount](#getVisibleCount--) | 获取文档大纲层次结构中所有级别的大纲项总数。 |
| [hasNext](#hasNext--) | 检查大纲层次结构中相对于此项的下一个项是否存在。 |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | 在指定位置将大纲项插入集合。 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [isSynchronized](#isSynchronized--) | 获取指示对该集合的访问是否同步（线程安全）的值。 |
| [iterator](#iterator--) | 返回一个遍历集合的枚举器。 |
| [next](#next--) |  |
| [remove](#remove-int-) | 按索引删除项目。 |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | 尚不支持。始终抛出 NotImplementedException。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | 设置此大纲项的操作。 |
| [setBold](#setBold-boolean-) | 设置此大纲项标题文本的粗体标志 |
| [setColor](#setColor-java.awt.Color-) | 设置此大纲项标题文本的颜色。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | 设置此大纲项的目标。 |
| [setItalic](#setItalic-boolean-) | 设置此大纲项标题文本的斜体标志 |
| [setOpen](#setOpen-boolean-) | 设置大纲项的打开状态（true/false）。 |
| [setTitle](#setTitle-java.lang.String-) | 设置此大纲项的标题。 |
| [size](#size--) | 集合项的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有级别上可见大纲项的数量。 |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
使用内部引擎大纲条目对象初始化此类的新实例。

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
使用根层次结构对象初始化大纲项实例。

### add {#add-com.aspose.pdf.OutlineItemCollection-}
向集合中添加大纲项。

### clear {#clear--}
```
public void clear()
```

清除集合中的所有项。

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
尚不支持。始终抛出 NotImplementedException。

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
将大纲条目复制到 System.Array 中，从特定的 System.Array 索引开始。

### delete {#delete--}
```
public void delete()
```

从文档大纲层次结构中删除此大纲项。

### delete {#delete-java.lang.String-}
从文档大纲层次结构中删除此大纲项。

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

使用索引从集合中获取大纲项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
OutlineItemCollection 对象。

### getAction {#getAction--}
```
public PdfAction getAction()
```

获取此大纲项的操作。

**Returns:**
PdfAction 值

### getBold {#getBold--}
```
public boolean getBold()
```

获取此大纲项标题文本的粗体标志

**Returns:**
布尔值

### getColor {#getColor--}
```
public Color getColor()
```

获取此大纲项标题文本的颜色。

**Returns:**
颜色值

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

获取此大纲项的目标。

**Returns:**
IAppointment 值

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

仅内部使用

**Returns:**
IPdfDictionary 对象

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

仅内部使用

**Returns:**
IPdfObject 对象

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

获取表示大纲层次结构中第一个顶级项的大纲项。

**Returns:**
OutlineItemCollection 值

### getItalic {#getItalic--}
```
public boolean getItalic()
```

获取此大纲项标题文本的斜体标志

**Returns:**
布尔值

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

获取表示大纲层次结构中最后一个顶级项的大纲项。

**Returns:**
OutlineItemCollection 值

### getLevel {#getLevel--}
```
public int getLevel()
```

获取大纲项的层级级别。

**Returns:**
int 值

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

获取表示相对于此项在大纲层次结构中下一个项的大纲项。

**Returns:**
OutlineItemCollection 值

### getOpen {#getOpen--}
```
public boolean getOpen()
```

获取大纲项的打开状态（true/false）。

**Returns:**
布尔值

### getParent {#getParent--}
```
public Outlines getParent()
```

获取此大纲项在大纲层次结构中的父对象。

**Returns:**
Object 值

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

获取表示相对于此项在大纲层次结构中上一个项的大纲项。

**Returns:**
OutlineItemCollection 值

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问此集合的对象。

**Returns:**
Object 值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取此大纲项的标题。

**Returns:**
字符串值

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

获取文档大纲层次结构中所有级别的大纲项总数。

**Returns:**
int 值

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

检查大纲层次结构中相对于此项的下一个项是否存在。

**Returns:**
布尔值

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
在指定位置将大纲项插入集合。

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示集合是否为只读。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对该集合的访问是否同步（线程安全）的值。

**Returns:**
布尔值

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
一个可用于遍历集合的 System.Collections.IEnumerator 对象。

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

按索引删除项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 要删除的项的索引。 |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
尚不支持。始终抛出 NotImplementedException。

### setAction {#setAction-com.aspose.pdf.PdfAction-}
设置此大纲项的操作。

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

设置此大纲项标题文本的粗体标志

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setColor {#setColor-java.awt.Color-}
设置此大纲项标题文本的颜色。

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
设置此大纲项的目标。

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

设置此大纲项标题文本的斜体标志

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

设置大纲项的打开状态（true/false）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTitle {#setTitle-java.lang.String-}
设置此大纲项的标题。

### size {#size--}
```
public int size()
```

集合项的计数。请不要与 VisibleCount 混淆：VisibleCount 获取所有级别上可见大纲项的数量。

**Returns:**
int 值
