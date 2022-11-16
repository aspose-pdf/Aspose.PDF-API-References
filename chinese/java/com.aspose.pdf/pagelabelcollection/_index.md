---
title: PageLabelCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示页面标签集合的类。
type: docs
weight: 263
url: /zh/java/com.aspose.pdf/pagelabelcollection/
---
**遗产：**
java.lang.Object
```
public class PageLabelCollection
```

表示页面标签集合的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLabel(int pageIndex)](#getLabel-int-) | 通过页面索引获取页面标签（页面索引从0开始）。 |
| [getPages()](#getPages--) | 获取集合中的页面索引。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLabel(int pageIndex)](#removeLabel-int-) | 按页面索引删除标签（页面索引从 0 开始）。 |
| [toString()](#toString--) |  |
| [updateLabel(int pageIndex, PageLabel pageLabel)](#updateLabel-int-com.aspose.pdf.PageLabel-) | 更新给定页面索引的标签（页面索引从 0 开始）。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getLabel(int pageIndex) {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```


通过页面索引获取页面标签（页面索引从0开始）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 页面索引。 |

**退货：**
[PageLabel](../../com.aspose.pdf/pagelabel) - 指定页面索引的页面标签，如果页面标签不存在，则为 null。
### getPages() {#getPages--}
```
public int[] getPages()
```


获取集合中的页面索引。

**退货：**
整数[] - 包含页面索引的整数数组。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLabel(int pageIndex) {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```


按页面索引删除标签（页面索引从 0 开始）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 必须删除标签的页面索引。 |

**退货：**
boolean - 如果操作成功执行则为真。
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### updateLabel(int pageIndex, PageLabel pageLabel) {#updateLabel-int-com.aspose.pdf.PageLabel-}
```
public void updateLabel(int pageIndex, PageLabel pageLabel)
```


更新给定页面索引的标签（页面索引从 0 开始）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | int | 更改页面标签的页面索引。 |
| pageLabel | [PageLabel](../../com.aspose.pdf/pagelabel) | 页面的新标签。 |

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
