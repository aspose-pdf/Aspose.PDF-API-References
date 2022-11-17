---
title: PrintController
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表打印控制器。
type: docs
weight: 294
url: /zh/java/com.aspose.pdf/printcontroller/
---
**遗产：**
java.lang.Object, com.aspose.ms.System.Drawing.Printing.PrintController

**所有已实现的接口：**
com.aspose.ms.System.IDisposable
```
public final class PrintController extends System.Drawing.Printing.PrintController implements System.IDisposable
```

代表打印控制器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PrintController()](#PrintController--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) | 处置实例 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | 设置文件名 |
| [hashCode()](#hashCode--) |  |
| [isPreview()](#isPreview--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | 仅供内部使用 |
| [onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | 仅供内部使用 |
| [onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | 仅供内部使用 |
| [onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | 仅供内部使用 |
| [onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | 仅供内部使用 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 设置文件名 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintController() {#PrintController--}
```
public PrintController()
```


### dispose() {#dispose--}
```
public final void dispose()
```


处置实例

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
### getFileName() {#getFileName--}
```
public final String getFileName()
```


设置文件名

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isPreview() {#isPreview--}
```
public boolean isPreview()
```




**退货：**
布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public void onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


仅供内部使用

在页面结束打印时触发。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | 内部实例（要打印的文档） |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | 内部实例（事件参数） |

### onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


仅供内部使用

在页面结束打印时触发。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | 内部实例（要打印的文档） |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | 内部实例（事件参数） |

### onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public System.Drawing.Graphics onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


仅供内部使用

在页面开始打印时触发。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | 内部实例（要打印的文档） |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | 内部实例（事件参数） |

**退货：**
com.aspose.ms.System.Drawing.Graphics - 内部实例
### onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public Graphics2D onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


仅供内部使用

在页面开始打印时触发。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | 内部实例（要打印的文档） |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | 内部实例（事件参数） |

**退货：**
java.awt.Graphics2D - 带有打印页面的 Graphics2D 实例。
### onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


仅供内部使用

在页面开始打印时触发。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | 内部实例（要打印的文档） |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | 内部实例（事件参数） |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


设置文件名

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
