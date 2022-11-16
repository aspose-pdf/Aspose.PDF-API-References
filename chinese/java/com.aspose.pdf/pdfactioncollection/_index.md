---
title: PdfActionCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类描述动作列表。
type: docs
weight: 276
url: /zh/java/com.aspose.pdf/pdfactioncollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public class PdfActionCollection implements Iterable<PdfAction>
```

类描述动作列表。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | 将动作添加到动作列表。 |
| [delete(int index)](#delete-int-) | 按索引删除操作。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取操作计数。 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引获取操作。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器。 |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | 内部方法 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


将动作添加到动作列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 实例要添加的操作。 |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


按索引删除操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的操作索引。 |

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
public int getCount()
```


获取操作计数。

**退货：**
int - 整数值
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


通过其索引获取操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 动作指标值。 |

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) - 如果找到 PdfAction 索引；否则，抛出
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<PdfAction> iterator()
```


获取枚举器。

**退货：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.PdfAction> - PDfAction 枚举器。
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator<PdfAction> iterator_Rename_Namesake()
```


内部方法

**退货：**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> - 内部对象。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
