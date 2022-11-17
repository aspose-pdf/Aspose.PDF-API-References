---
title: JavascriptAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 javascript 操作的类。
type: docs
weight: 182
url: /zh/java/com.aspose.pdf/javascriptaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class JavascriptAction extends PdfAction
```

表示 javascript 操作的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JavascriptAction(String javaScript)](#JavascriptAction-java.lang.String-) | 创建描述操作的 PDF 字典。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [getScript()](#getScript--) | 获取 javascript 代码。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScript(String value)](#setScript-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JavascriptAction(String javaScript) {#JavascriptAction-java.lang.String-}
```
public JavascriptAction(String javaScript)
```


创建描述操作的 PDF 字典。

构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| javaScript | java.lang.String | JavaScript 代码。 |

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
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


接下来的动作依次进行。

**退货：**
[ActionCollection](../../com.aspose.pdf/actioncollection) 动作集合对象
### getScript() {#getScript--}
```
public String getScript()
```


获取 javascript 代码。

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




### setScript(String value) {#setScript-java.lang.String-}
```
public void setScript(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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
