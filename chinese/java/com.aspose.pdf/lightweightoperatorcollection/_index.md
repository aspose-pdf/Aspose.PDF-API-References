---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "轻量级操作符集合。旨在在底层内容流未附加的情况下使用，此时仅需要操作符集合作为结果。"
type: docs
weight: 2700
url: /zh/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

轻量级操作符集合。旨在在底层内容流未附加的情况下使用，此时仅需要操作符集合作为结果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | 初始化对象 |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | 初始化对象 |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | 初始化对象 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | 添加操作符 |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | 添加 LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | 取消上一次更新。当更改不应触发内容更新时可以调用此方法。 |
| [clear](#clear--) | 清空集合。 |
| [contains](#contains-com.aspose.pdf.Operator-) | 检查项是否在集合中。 |
| [deleteUnrestricted](#deleteUnrestricted-int-) | 内部删除 Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> 根据索引获取操作符。 </p> <hr> <pre> 示例演示如何通过索引获取页面内容的操作符。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | 供内部使用的 getUnrestricted 操作符 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | 插入操作符 |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | 指示集合是否受限于快速文本提取 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [iterator](#iterator--) | 返回迭代器 |
| [remove](#remove-com.aspose.pdf.Operator-) | 从集合中移除操作符。 |
| [resumeUpdate](#resumeUpdate--) | 恢复文档更新。如果有任何挂起的更改，则更新内容流。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | 通过索引设置运算符。 <hr> <pre> 示例演示如何通过索引获取页面内容的运算符。 Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | 运算符计数 |
| [suppressUpdate](#suppressUpdate--) | 抑制更新内容数据。内容流在调用 ResumeUpdate 之前不会更新。 |
| [toList](#toList--) | 返回运算符列表。 |
| [updateData](#updateData--) | 内部 |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

初始化对象

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
初始化对象

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
初始化对象

### add {#add-com.aspose.pdf.Operator-}
添加操作符

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
添加 LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

取消上一次更新。当更改不应触发内容更新时可以调用此方法。

### clear {#clear--}
```
public void clear()
```

清空集合。

### contains {#contains-com.aspose.pdf.Operator-}
检查项是否在集合中。

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

内部删除 Unrestrictedelement

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> 根据索引获取操作符。 </p> <hr> <pre> 示例演示如何通过索引获取页面内容的操作符。 Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 运算符的索引。编号从 1 开始。 |

**Returns:**
来自请求索引的运算符

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

供内部使用的 getUnrestricted 操作符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

**Returns:**
运算符对象

### insert {#insert-int-com.aspose.pdf.Operator-}
插入操作符

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

指示集合是否受限于快速文本提取

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示集合是否为只读。

**Returns:**
布尔值

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

返回迭代器

**Returns:**
{@code IGenericEnumerator<Operator>} 对象

### remove {#remove-com.aspose.pdf.Operator-}
从集合中移除操作符。

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

恢复文档更新。如果有任何挂起的更改，则更新内容流。

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
通过索引设置运算符。 <hr> <pre> 示例演示如何通过索引获取页面内容的运算符。 Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

运算符计数

**Returns:**
int 值

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

抑制更新内容数据。内容流在调用 ResumeUpdate 之前不会更新。

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

返回运算符列表。

**Returns:**
运算符列表。

### updateData {#updateData--}
```
public void updateData()
```

内部
