---
title: FitBVExplicitDestination
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示显示页面的显式目标，该页面的水平坐标 left 位于窗口的左边缘，并且页面的内容放大到足以适合窗口内其边界框的整个高度。
type: docs
weight: 121
url: /zh/java/com.aspose.pdf/fitbvexplicitdestination/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitBVExplicitDestination extends ExplicitDestination
```

表示显示页面的显式目标，该页面的水平坐标 left 位于窗口的左边缘，并且页面的内容放大到足以适合窗口内其边界框的整个高度。 left 的空值指定该参数的当前值将保持不变。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitBVExplicitDestination(Page page, double left)](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | 创建实例并通过 DOM 页面对象和左参数对其进行初始化。 |
| [FitBVExplicitDestination(Document document, int pageNumber, double left)](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | 创建远程显式目标。 |
| [FitBVExplicitDestination(int pageNumber, double left)](#FitBVExplicitDestination-int-double-) | 创建远程显式目标。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | 获取位于窗口左边缘的水平坐标 left。 |
| [getPage()](#getPage--) | 获取目标页面对象 |
| [getPageNumber()](#getPageNumber--) | 获取目标页码 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 将对象状态转换为字符串值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitBVExplicitDestination(Page page, double left) {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
```
public FitBVExplicitDestination(Page page, double left)
```


创建实例并通过 DOM 页面对象和左参数对其进行初始化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM 页面对象。 |
| left | double | 位于窗口左边缘的水平坐标 left。 |

### FitBVExplicitDestination(Document document, int pageNumber, double left) {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
```
public FitBVExplicitDestination(Document document, int pageNumber, double left)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | 包含此对象的父文档。 |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 位于窗口左边缘的水平坐标 left。 |

### FitBVExplicitDestination(int pageNumber, double left) {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 位于窗口左边缘的水平坐标 left。 |

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
### getLeft() {#getLeft--}
```
public double getLeft()
```


获取位于窗口左边缘的水平坐标 left。

**退货：**
双倍价值
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


将对象状态转换为字符串值。示例：“1 FitBV 100”。

**退货：**
java.lang.String - 表示对象状态的字符串值。
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
