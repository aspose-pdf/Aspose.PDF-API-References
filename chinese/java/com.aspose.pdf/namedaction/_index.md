---
title: NamedAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PDF 查看器应用程序应支持的命名操作。
type: docs
weight: 225
url: /zh/java/com.aspose.pdf/namedaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class NamedAction extends PdfAction
```

表示 PDF 查看器应用程序应支持的命名操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NamedAction(int action)](#NamedAction-int-) | 命名操作类的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取要执行的操作。 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setName(String value)](#setName-java.lang.String-) | 设置要执行的操作。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NamedAction(int action) {#NamedAction-int-}
```
public NamedAction(int action)
```


命名操作类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| action | int | 创建此对象的操作。 |

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
### getName() {#getName--}
```
public String getName()
```


获取要执行的操作。

**退货：**
java.lang.String - 字符串值
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


接下来的动作依次进行。

**退货：**
[ActionCollection](../../com.aspose.pdf/actioncollection) 动作集合对象
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




### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

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
