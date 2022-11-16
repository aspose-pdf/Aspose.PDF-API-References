---
title: Id
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文件标识符结构。
type: docs
weight: 165
url: /zh/java/com.aspose.pdf/id/
---
**遗产：**
java.lang.Object
```
public class Id
```

表示文件标识符结构。

--------------------

```
Document doc = new Document("example.pdf");
 String original = doc.getId().getOriginal();
 String modified = doc.getId().getModified();
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getModified()](#getModified--) | 根据上次更新时文档的内容更改标识符。 |
| [getOriginal()](#getOriginal--) | 基于文档最初创建时的内容的永久标识符。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
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
### getModified() {#getModified--}
```
public String getModified()
```


根据上次更新时文档的内容更改标识符。

**退货：**
java.lang.String - 字符串值
### getOriginal() {#getOriginal--}
```
public String getOriginal()
```


基于文档最初创建时的内容的永久标识符。

**退货：**
java.lang.String - 字符串值
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
