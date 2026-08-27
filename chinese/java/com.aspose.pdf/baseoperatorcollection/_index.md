---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符集合的基类。"
type: docs
weight: 270
url: /zh/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

表示运算符集合的基类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | 向集合中添加新操作符。 |
| [cancelUpdate](#cancelUpdate--) | 取消上一次更新。当更改不应触发内容更新时可以调用此方法。 |
| [clear](#clear--) | 清空集合。 |
| [contains](#contains-com.aspose.pdf.Operator-) | 检查项是否在集合中。 |
| [deleteUnrestricted](#deleteUnrestricted-int-) | 内部 |
| [get_Item](#get_Item-int-) | 根据索引获取操作符。 |
| [getUnrestricted](#getUnrestricted-int-) | 仅供内部使用 |
| [insert](#insert-int-com.aspose.pdf.Operator-) | 在集合中插入操作符。 |
| [isEmpty](#isEmpty--) | 如果集合为空，则返回 TRUE。 |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | 指示集合是否受限于快速文本提取 |
| [isReadOnly](#isReadOnly--) | 如果集合为只读，则返回 true。 |
| [iterator](#iterator--) | 返回集合的枚举器 |
| [remove](#remove-com.aspose.pdf.Operator-) | 从集合中移除操作符。 |
| [resumeUpdate](#resumeUpdate--) | 恢复文档更新。如果有任何挂起的更改，则更新内容流。 |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | 通过索引设置操作符。 |
| [size](#size--) | 获取集合中操作符的计数。 |
| [suppressUpdate](#suppressUpdate--) | 抑制更新内容数据。内容流在调用 ResumeUpdate 之前不会更新。 |
| [toList](#toList--) | 返回 opetator 列表。 |
| [updateData](#updateData--) | 内部 |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
向集合中添加新操作符。

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

取消上一次更新。当更改不应触发内容更新时可以调用此方法。

### clear {#clear--}
```
public abstract void clear()
```

清空集合。

### contains {#contains-com.aspose.pdf.Operator-}
检查项是否在集合中。

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

内部

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

根据索引获取操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 运算符的索引。编号从 1 开始。 |

**Returns:**
来自请求索引的运算符

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

仅供内部使用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

**Returns:**
运算符对象

### insert {#insert-int-com.aspose.pdf.Operator-}
在集合中插入操作符。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

如果集合为空，则返回 TRUE。

**Returns:**
布尔值

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

指示集合是否受限于快速文本提取

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

如果集合为只读，则返回 true。

**Returns:**
布尔值

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

返回集合的枚举器

**Returns:**
集合枚举器

### remove {#remove-com.aspose.pdf.Operator-}
从集合中移除操作符。

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

恢复文档更新。如果有任何挂起的更改，则更新内容流。

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
通过索引设置操作符。

### size {#size--}
```
public abstract int size()
```

获取集合中操作符的计数。

**Returns:**
整数值

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

抑制更新内容数据。内容流在调用 ResumeUpdate 之前不会更新。

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

返回 opetator 列表。

**Returns:**
操作符列表。

### updateData {#updateData--}
```
public abstract void updateData()
```

内部
