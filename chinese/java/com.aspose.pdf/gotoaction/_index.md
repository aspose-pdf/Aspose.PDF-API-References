---
title: GoToAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示将视图更改为指定目标页面位置和放大系数的转到操作。
type: docs
weight: 144
url: /zh/java/com.aspose.pdf/gotoaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class GoToAction extends PdfAction
```

表示将视图更改为指定目标（页面、位置和放大系数）的转到操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GoToAction(int page)](#GoToAction-int-) | GoToAction 类的构造函数。 |
| [GoToAction(Page page)](#GoToAction-com.aspose.pdf.Page-) | GoToAction 类的构造函数。 |
| [GoToAction(Page page, int type, double[] values)](#GoToAction-com.aspose.pdf.Page-int-double...-) | GoToAction 类的构造函数。 |
| [GoToAction(ExplicitDestination destination)](#GoToAction-com.aspose.pdf.ExplicitDestination-) | 构造函数。 |
| [GoToAction()](#GoToAction--) | 构造函数。 |
| [GoToAction(Document doc, String name)](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | 与命名目标相关联的操作。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | 获取要跳转到的目的地。 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | 设置要跳转到的目的地。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GoToAction(int page) {#GoToAction-int-}
```
public GoToAction(int page)
```


GoToAction 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 整数值 |

### GoToAction(Page page) {#GoToAction-com.aspose.pdf.Page-}
```
public GoToAction(Page page)
```


GoToAction 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要跳转到的页面目标对象。 |

### GoToAction(Page page, int type, double[] values) {#GoToAction-com.aspose.pdf.Page-int-double...-}
```
public GoToAction(Page page, int type, double[] values)
```


GoToAction 类的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 目的地页面。 |
| type | int | 目的地类型。 |
| values | double[] | 动作参数。 |

### GoToAction(ExplicitDestination destination) {#GoToAction-com.aspose.pdf.ExplicitDestination-}
```
public GoToAction(ExplicitDestination destination)
```


构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | 明确的目的地。 |

### GoToAction() {#GoToAction--}
```
public GoToAction()
```


构造函数。

### GoToAction(Document doc, String name) {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
```
public GoToAction(Document doc, String name)
```


与命名目标相关联的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | 将在其中创建操作的文档。 |
| name | java.lang.String | 目的地名称。 |

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
[IAppointment](../../com.aspose.pdf/iappointment) - 预约值
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
| value | [IAppointment](../../com.aspose.pdf/iappointment) | 预约值 |

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
