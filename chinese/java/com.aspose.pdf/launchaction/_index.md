---
title: LaunchAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示启动应用程序或打开或打印文档的启动操作。
type: docs
weight: 187
url: /zh/java/com.aspose.pdf/launchaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class LaunchAction extends PdfAction
```

表示启动应用程序或打开或打印文档的启动操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LaunchAction(String file)](#LaunchAction-java.lang.String-) | 创建启动操作。 |
| [LaunchAction(IDocument document, String file)](#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-) | 创建启动操作。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | 获取要启动的应用程序或要打开或打印的文档。 |
| [getNewWindow()](#getNewWindow--) | 获取一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFile(String value)](#setFile-java.lang.String-) | 设置要启动的应用程序或要打开或打印的文档。 |
| [setNewWindow(int value)](#setNewWindow-int-) | 设置一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LaunchAction(String file) {#LaunchAction-java.lang.String-}
```
public LaunchAction(String file)
```


创建启动操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 要启动的文件。 |

### LaunchAction(IDocument document, String file) {#LaunchAction-com.aspose.pdf.IDocument-java.lang.String-}
```
public LaunchAction(IDocument document, String file)
```


创建启动操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 将在其中创建操作的文档。 |
| file | java.lang.String | 要启动的文件。 |

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
### getFile() {#getFile--}
```
public String getFile()
```


获取要启动的应用程序或要打开或打印的文档。

**退货：**
java.lang.String - 字符串值
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


获取一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。

**退货：**
int - ExtendedBoolean 元素
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




### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


设置要启动的应用程序或要打开或打印的文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


设置一个标志，指定是否在新窗口中打开目标文档（仅影响 PDF 文档）。扩展布尔值

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 扩展布尔元素 |

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
