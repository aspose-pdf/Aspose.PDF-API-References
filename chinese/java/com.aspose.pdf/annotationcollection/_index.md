---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示注释集合的类。"
type: docs
weight: 80
url: /zh/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

表示注释集合的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | AnnotationCollection 的构造函数。为给定页面上的注释创建注释集合。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者以处理注释。 |
| [add](#add-com.aspose.pdf.Annotation-) | 向集合中添加注释。 |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | 向集合中添加注释。如果页面已旋转，则相应地重新计算注释矩形。 |
| [clear](#clear--) | 从集合中删除所有注释。 |
| [contains](#contains-com.aspose.pdf.Annotation-) | 检查指定的注释是否属于集合。 |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | 将注释数组复制到集合中。 |
| [delete](#delete--) | 从集合中删除所有注释。 |
| [delete](#delete-com.aspose.pdf.Annotation-) | 从集合中删除所有注释。 |
| [delete](#delete-int-) | 按索引从集合中删除注释。 |
| [findByName](#findByName-java.lang.String-) | 按名称返回注释。 |
| [get_Item](#get_Item-int-) | 要获取的元素索引。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问 com.aspose.pdf.AnnotationCollection 的对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值。 |
| [isSynchronized](#isSynchronized--) | 获取指示对 com.aspose.pdf.AnnotationCollection 的访问是否已同步（线程安全）的值。 |
| [iterator](#iterator--) | 返回集合枚举器。 |
| [remove](#remove-com.aspose.pdf.Annotation-) | 从集合中删除指定的注释。 |
| [size](#size--) | 获取集合中注释的计数。 |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
AnnotationCollection 的构造函数。为给定页面上的注释创建注释集合。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者以处理注释。

### add {#add-com.aspose.pdf.Annotation-}
向集合中添加注释。

### add {#add-com.aspose.pdf.Annotation-boolean-}
向集合中添加注释。如果页面已旋转，则相应地重新计算注释矩形。

### clear {#clear--}
```
public void clear()
```

从集合中删除所有注释。

### contains {#contains-com.aspose.pdf.Annotation-}
检查指定的注释是否属于集合。

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
将注释数组复制到集合中。

### delete {#delete--}
```
public void delete()
```

从集合中删除所有注释。

### delete {#delete-com.aspose.pdf.Annotation-}
从集合中删除所有注释。

### delete {#delete-int-}
```
public void delete(int index)
```

按索引从集合中删除注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 将被删除的注释的索引。 |

### findByName {#findByName-java.lang.String-}
按名称返回注释。

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

要获取的元素索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 索引值从一开始。 |

**Returns:**
注释对象

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问 com.aspose.pdf.AnnotationCollection 的对象。

**Returns:**
用于同步的对象

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否为只读的值。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对 com.aspose.pdf.AnnotationCollection 的访问是否已同步（线程安全）的值。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

返回集合枚举器。

**Returns:**
枚举器对象

### remove {#remove-com.aspose.pdf.Annotation-}
从集合中删除指定的注释。

### size {#size--}
```
public int size()
```

获取集合中注释的计数。

**Returns:**
int 值
