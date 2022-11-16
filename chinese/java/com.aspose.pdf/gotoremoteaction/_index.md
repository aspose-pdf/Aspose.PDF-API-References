---
title: GoToRemoteAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个远程转到操作，类似于普通的转到操作，但跳转到另一个 PDF 文件而不是当前文件中的目标。
type: docs
weight: 145
url: /zh/java/com.aspose.pdf/gotoremoteaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction), [com.aspose.pdf.GoToAction](../../com.aspose.pdf/gotoaction)
```
public final class GoToRemoteAction extends GoToAction
```

表示一个远程转到操作，类似于普通的转到操作，但跳转到另一个 PDF 文件而不是当前文件中的目标。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GoToRemoteAction(String remotePdf, int remotePageNumber)](#GoToRemoteAction-java.lang.String-int-) | 初始化 GoToRemoteAction 对象。 |
| [GoToRemoteAction(String remotePdf, ExplicitDestination destination)](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | 初始化 GoToRemoteAction 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | 获取要跳转到的目的地。 |
| [getFile()](#getFile--) | 获取目标所在文件的规范。 |
| [getNewWindow()](#getNewWindow--) | 获取一个标志，该标志指定是否在新窗口中打开目标文档。 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | 设置要跳转到的目的地。 |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | 设置目标所在文件的规范。 |
| [setNewWindow(int value)](#setNewWindow-int-) | 设置一个标志，指定是否在新窗口中打开目标文档。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GoToRemoteAction(String remotePdf, int remotePageNumber) {#GoToRemoteAction-java.lang.String-int-}
```
public GoToRemoteAction(String remotePdf, int remotePageNumber)
```


初始化 GoToRemoteAction 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| remotePdf | java.lang.String | 目标 PDF 文档。 |
| remotePageNumber | int | 目标页码。 |

### GoToRemoteAction(String remotePdf, ExplicitDestination destination) {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
```
public GoToRemoteAction(String remotePdf, ExplicitDestination destination)
```


初始化 GoToRemoteAction 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| remotePdf | java.lang.String | 目标 PDF 文档。 |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | PDF 文档中的目标。 |

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
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


获取要跳转到的目的地。

**退货：**
[IAppointment](../../com.aspose.pdf/iappointment) - 跳跃的目的地
### getFile() {#getFile--}
```
public FileSpecification getFile()
```


获取目标所在文件的规范。

**退货：**
[FileSpecification](../../com.aspose.pdf/filespecification) 文件规范对象
### getNewWindow() {#getNewWindow--}
```
public int getNewWindow()
```


获取一个标志，该标志指定是否在新窗口中打开目标文档。

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




### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


设置要跳转到的目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 跳跃的目的地 |

### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


设置目标所在文件的规范。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | 文件规格值 |

### setNewWindow(int value) {#setNewWindow-int-}
```
public void setNewWindow(int value)
```


设置一个标志，指定是否在新窗口中打开目标文档。

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
