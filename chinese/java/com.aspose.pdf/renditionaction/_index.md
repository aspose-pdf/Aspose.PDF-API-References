---
title: RenditionAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 控制多媒体内容播放的再现动作。
type: docs
weight: 306
url: /zh/java/com.aspose.pdf/renditionaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class RenditionAction extends PdfAction
```

控制多媒体内容播放的再现动作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenditionAction(String mediaFile, ScreenAnnotation screen)](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | 创建演绎动作。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getJavaScript()](#getJavaScript--) | 获取或设置与操作关联的 JavaScript 代码。 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [getRendition()](#getRendition--) | 获取或设置与操作关联的再现。 |
| [getRenditionOperation()](#getRenditionOperation--) | 触发操作时要执行的操作。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setJavaScript(String value)](#setJavaScript-java.lang.String-) | 获取或设置与操作关联的 JavaScript 代码。 |
| [setRenditionOperation(int value)](#setRenditionOperation-int-) | 触发操作时要执行的操作。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenditionAction(String mediaFile, ScreenAnnotation screen) {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
```
public RenditionAction(String mediaFile, ScreenAnnotation screen)
```


创建演绎动作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mediaFile | java.lang.String | 多媒体文件的路径。 |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | RenditionAction 将与之绑定的 ScreenAnnotation 对象。 |

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
### getJavaScript() {#getJavaScript--}
```
public final String getJavaScript()
```


获取或设置与操作关联的 JavaScript 代码。

**退货：**
java.lang.String - 字符串值
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


接下来的动作依次进行。

**退货：**
[ActionCollection](../../com.aspose.pdf/actioncollection) 动作集合对象
### getRendition() {#getRendition--}
```
public final Rendition getRendition()
```


获取或设置与操作关联的再现。

**退货：**
[Rendition](../../com.aspose.pdf/rendition) - 演绎实例
### getRenditionOperation() {#getRenditionOperation--}
```
public final int getRenditionOperation()
```


触发操作时要执行的操作。

**退货：**
int - RenditionOperation 元素
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




### setJavaScript(String value) {#setJavaScript-java.lang.String-}
```
public final void setJavaScript(String value)
```


获取或设置与操作关联的 JavaScript 代码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 起始值 |

### setRenditionOperation(int value) {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```


触发操作时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | RenditionOperation 元素 |

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
