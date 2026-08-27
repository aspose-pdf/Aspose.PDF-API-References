---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示字体来源集合。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
可迭代 < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

表示字体来源集合。

## 字段

| 字段 | 描述 |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged 事件 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | 初始化集合对象 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | 向集合中添加新的字体源对象。 |
| [clear](#clear--) | 清除字体源集合。 |
| [contains](#contains-com.aspose.pdf.FontSource-) | 确定元素是否在集合中。 |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | 将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [delete](#delete-com.aspose.pdf.FontSource-) | 删除字体源元素。 |
| [getItem](#getItem-int-) | 获取指定索引处的字体元素。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问集合的对象。 |
| [isSynchronized](#isSynchronized--) | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.FontSource-) | 删除字体源元素。 |
| [size](#size--) | 获取集合中实际包含的 Font 对象元素的数量。 |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

CollectionChanged 事件

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

初始化集合对象

### add {#add-com.aspose.pdf.FontSource-}
向集合中添加新的字体源对象。

### clear {#clear--}
```
public void clear()
```

清除字体源集合。

### contains {#contains-com.aspose.pdf.FontSource-}
确定元素是否在集合中。

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。

### delete {#delete-com.aspose.pdf.FontSource-}
删除字体源元素。

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

获取指定索引处的字体元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
字体源对象。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问集合的对象。

**Returns:**
对象元素

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对集合的访问是否已同步（线程安全）的值。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.FontSource-}
删除字体源元素。

### size {#size--}
```
public int size()
```

获取集合中实际包含的 Font 对象元素的数量。

**Returns:**
int 值
