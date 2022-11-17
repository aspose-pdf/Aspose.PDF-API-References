---
title: XFormCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示 XFormCollection 的集合。
type: docs
weight: 408
url: /zh/java/com.aspose.pdf/xformcollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class XFormCollection implements Iterable<XForm>
```

类表示 XFormCollection 的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(XForm xform)](#add-com.aspose.pdf.XForm-) | 将新的 XForm 添加到集合中。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(XForm item)](#contains-com.aspose.pdf.XForm-) | 确定集合是否包含特定值。 |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | 将 XFormCollection 复制到集合中。 |
| [delete()](#delete--) | 从集合中删除所有 XForm。 |
| [delete(int index)](#delete-int-) | 从收集器中删除 XForm |
| [delete(String name)](#delete-java.lang.String-) | 按表单名称从集合中删除 XForm。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormName(XForm form)](#getFormName-com.aspose.pdf.XForm-) | 返回此表单集合中的表单名称 |
| [getSyncRoot()](#getSyncRoot--) | 同步对象。 |
| [get_Item(int index)](#get-Item-int-) | 按索引返回 XForm。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 按名称返回 XForm。 |
| [hasForm(String formName)](#hasForm-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 如果对象已同步，则返回 true。 |
| [iterator()](#iterator--) | 返回集合枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XForm item)](#remove-com.aspose.pdf.XForm-) | 从集合中删除指定的项目。 |
| [size()](#size--) | 获取集合中 XForms 的数量。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XForm xform) {#add-com.aspose.pdf.XForm-}
```
public void add(XForm xform)
```


将新的 XForm 添加到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xform | [XForm](../../com.aspose.pdf/xform) | 要添加到集合中的 XForm |

### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(XForm item) {#contains-com.aspose.pdf.XForm-}
```
public boolean contains(XForm item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


将 XFormCollection 复制到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | 要复制的 XForm 数组 |
| index | int | 将复制 XFormCollection 的索引 |

### delete() {#delete--}
```
public void delete()
```


从集合中删除所有 XForm。

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


从收集器中删除 XForm

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 必须删除的 XForm 的索引 |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


按表单名称从集合中删除 XForm。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的 XForm 的名称。 |

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
### getFormName(XForm form) {#getFormName-com.aspose.pdf.XForm-}
```
public String getFormName(XForm form)
```


返回此表单集合中的表单名称

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | 搜索姓名的表格 |

**退货：**
java.lang.String - 集合中的表单名称；如果集合中不包含表单，则为空
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


同步对象。

**退货：**
java.lang.Object - 对象
### get_Item(int index) {#get-Item-int-}
```
public XForm get_Item(int index)
```


按索引返回 XForm。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | XFormCollection 的索引。 XForms 编号从 1 开始 |

**退货：**
[XForm](../../com.aspose.pdf/xform) 检索 XForm
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XForm get_Item(String name)
```


按名称返回 XForm。如果未找到具有指定名称的 XForm，则抛出异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 变形的名称 |

**退货：**
[XForm](../../com.aspose.pdf/xform) 变形对象
### hasForm(String formName) {#hasForm-java.lang.String-}
```
public boolean hasForm(String formName)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formName | java.lang.String |  |

**退货：**
布尔值
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


如果对象已同步，则返回 true。

**退货：**
布尔值 - 布尔值
### iterator() {#iterator--}
```
public Iterator<XForm> iterator()
```


返回集合枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.XForm> - 集合枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XForm item) {#remove-com.aspose.pdf.XForm-}
```
public boolean remove(XForm item)
```


从集合中删除指定的项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | 要删除的对象 |

**退货：**
布尔值 - 如果项目已从集合中删除，则为 true；否则，假的。
### size() {#size--}
```
public int size()
```


获取集合中 XForms 的数量。

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
