---
title: AnnotationCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示注释集合的类。
type: docs
weight: 17
url: /zh/java/com.aspose.pdf/annotationcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class AnnotationCollection implements Iterable<Annotation>
```

表示注释集合的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnnotationCollection(Page page)](#AnnotationCollection-com.aspose.pdf.Page-) | AnnotationCollection 的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者处理注释。 |
| [add(Annotation annotation)](#add-com.aspose.pdf.Annotation-) | 向集合添加注释。 |
| [add(Annotation annotation, boolean considerRotation)](#add-com.aspose.pdf.Annotation-boolean-) | 向集合添加注释。 |
| [clear()](#clear--) | 从集合中删除所有注释。 |
| [contains(Annotation annotation)](#contains-com.aspose.pdf.Annotation-) | 检查指定的注释是否属于集合。 |
| [copyTo(Annotation[] array, int index)](#copyTo-com.aspose.pdf.Annotation---int-) | 将注释数组复制到集合中。 |
| [delete()](#delete--) | 从集合中删除所有注释。 |
| [delete(Annotation annotation)](#delete-com.aspose.pdf.Annotation-) | 从集合中删除指定的注释。 |
| [delete(int index)](#delete-int-) | 按索引从集合中删除注释。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByName(String name)](#findByName-java.lang.String-) | 按其名称返回注释。 |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取可用于同步访问 com.aspose.pdf.AnnotationCollection 的对象。 |
| [get_Item(int index)](#get-Item-int-) | 要获取的元素的索引。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 获取一个值，该值指示对 com.aspose.pdf.AnnotationCollection 的访问是否同步（线程安全）。 |
| [iterator()](#iterator--) | 返回集合枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Annotation annotation)](#remove-com.aspose.pdf.Annotation-) | 从集合中删除指定的注释。 |
| [size()](#size--) | 获取集合中注释的计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnnotationCollection(Page page) {#AnnotationCollection-com.aspose.pdf.Page-}
```
public AnnotationCollection(Page page)
```


AnnotationCollection 的构造函数。为给定页面上的注释创建注释集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 注释的父页。 |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


接受访问者处理注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | 注释选择器对象。 |

### add(Annotation annotation) {#add-com.aspose.pdf.Annotation-}
```
public void add(Annotation annotation)
```


向集合添加注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 应添加的注释。 |

### add(Annotation annotation, boolean considerRotation) {#add-com.aspose.pdf.Annotation-boolean-}
```
public void add(Annotation annotation, boolean considerRotation)
```


向集合添加注释。如果页面旋转，则注释矩形将相应地重新计算。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 应添加的注释。 |
| considerRotation | boolean | 如果为 true 且页面旋转，则注释位置将根据页面旋转重新计算。 |

### clear() {#clear--}
```
public void clear()
```


从集合中删除所有注释。

### contains(Annotation annotation) {#contains-com.aspose.pdf.Annotation-}
```
public boolean contains(Annotation annotation)
```


检查指定的注释是否属于集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 要搜索的注释。 |

**退货：**
boolean - 布尔值 True - 如果找到注释；否则，假的。
### copyTo(Annotation[] array, int index) {#copyTo-com.aspose.pdf.Annotation---int-}
```
public void copyTo(Annotation[] array, int index)
```


将注释数组复制到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [Annotation\[\]](../../com.aspose.pdf/annotation) | 要复制到集合中的数组。 |
| index | int | colleciton 将被复制的起始索引。 |

### delete() {#delete--}
```
public void delete()
```


从集合中删除所有注释。

### delete(Annotation annotation) {#delete-com.aspose.pdf.Annotation-}
```
public void delete(Annotation annotation)
```


从集合中删除指定的注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 应删除的注释。 |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


按索引从集合中删除注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的注解索引。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### findByName(String name) {#findByName-java.lang.String-}
```
public final Annotation findByName(String name)
```


按其名称返回注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 注释的名称 |

**退货：**
[Annotation](../../com.aspose.pdf/annotation) 如果找到注释对象；否则为空。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


获取可用于同步访问 com.aspose.pdf.AnnotationCollection 的对象。

**退货：**
java.lang.Object - 同步对象
### get_Item(int index) {#get-Item-int-}
```
public Annotation get_Item(int index)
```


要获取的元素的索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引值从一开始。 |

**退货：**
[Annotation](../../com.aspose.pdf/annotation) - 注释对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


获取一个值，该值指示对 com.aspose.pdf.AnnotationCollection 的访问是否同步（线程安全）。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<Annotation> iterator()
```


返回集合枚举器。

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.Annotation> - 枚举器对象
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Annotation annotation) {#remove-com.aspose.pdf.Annotation-}
```
public boolean remove(Annotation annotation)
```


从集合中删除指定的注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 应删除的注释。 |

**退货：**
boolean - 布尔值 True - 如果找到注释；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中注释的计数。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
