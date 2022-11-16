---
title: ElementList
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示有序的元素集合。
type: docs
weight: 13
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public abstract class ElementList implements System.Collections.Generic.IGenericEnumerable<Element>
```

表示有序的元素集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addElement(Element element)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取 ElementList 中的元素数。 |
| [get_Item(int index)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [item(int index)](#item-int-) | 检索给定索引处的元素。 |
| [iterator()](#iterator--) | 获取循环访问元素集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addElement(Element element) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void addElement(Element element)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### addElement(Element element, boolean updatePdfDictionary) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
```
public abstract void addElement(Element element, boolean updatePdfDictionary)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
| updatePdfDictionary | boolean |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract int getCount()
```


获取 ElementList 中的元素数。

**退货：**
int - 整数值
### get_Item(int index) {#get-Item-int-}
```
public Element get_Item(int index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### item(int index) {#item-int-}
```
public abstract Element item(int index)
```


检索给定索引处的元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素列表的索引。 |

**退货：**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - 在集合中具有指定索引的 /Aspose.Pdf.LogicalStructure.Element。如果索引大于或等于列表中的元素数，则返回 null。
### iterator() {#iterator--}
```
public abstract System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


获取循环访问元素集合的枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element> - 用于遍历元素集合的枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public abstract void removeElement(Element element)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

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
