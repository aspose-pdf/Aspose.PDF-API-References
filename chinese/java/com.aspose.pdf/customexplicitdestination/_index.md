---
title: CustomExplicitDestination
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示自定义显式目标。
type: docs
weight: 79
url: /zh/java/com.aspose.pdf/customexplicitdestination/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class CustomExplicitDestination extends ExplicitDestination
```

表示自定义显式目标。
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPage()](#getPage--) | 获取目标页面对象 |
| [getPageNumber()](#getPageNumber--) | 获取目标页码 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 转换为页码。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createDestination(IDocument doc, int pageNumber, int type, double[] values) {#createDestination-com.aspose.pdf.IDocument-int-int-double...-}
```
public static ExplicitDestination createDestination(IDocument doc, int pageNumber, int type, double[] values)
```


创建 ExplicitDestination 子类的实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | 将在其中创建目标的文档。 |
| pageNumber | int | 页码。 |
| type | int | 目的地类型。 |
| values | double[] | 目的地特定值的数组。 |

**退货：**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - 明确的目标对象。
### createDestination(Page page, int type, double[] values) {#createDestination-com.aspose.pdf.Page-int-double...-}
```
public static ExplicitDestination createDestination(Page page, int type, double[] values)
```


创建 ExplicitDestination 子类的实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 目标页面的对象。 |
| type | int | 显式目标的类型。 |
| values | double[] | 双精度值数组。 |

**退货：**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - 明确的目标对象。
### createDestination(IPdfArray engineDest) {#createDestination-com.aspose.pdf.engine.data.IPdfArray-}
```
public static ExplicitDestination createDestination(IPdfArray engineDest)
```


创建 ExplicitDestination 子类的实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| engineDest | [IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) | 引擎目标对象。 |

**退货：**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - DOM 显式目标对象。
### createDestination(int pageNumber, int type, double[] values) {#createDestination-int-int-double...-}
```
public static ExplicitDestination createDestination(int pageNumber, int type, double[] values)
```


创建 ExplicitDestination 子类的实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 目标页码。 |
| type | int | 显式目标的类型。 |
| values | double[] | 双精度值数组。 |

**退货：**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - 明确的目标对象。
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
### getPage() {#getPage--}
```
public Page getPage()
```


获取目标页面对象

**退货：**
[Page](../../com.aspose.pdf/page) 页面对象
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取目标页码

**退货：**
int - 整数值
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


转换为页码。

返回页码目标

**退货：**
java.lang.String - 字符串解释。
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
