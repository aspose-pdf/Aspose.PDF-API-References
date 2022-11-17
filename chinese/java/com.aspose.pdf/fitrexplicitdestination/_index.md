---
title: FitRExplicitDestination
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示显示页面的显式目标，其内容放大到足以适合由坐标 left bottom right 和 toppentirely 在水平和垂直方向上指定的矩形。
type: docs
weight: 124
url: /zh/java/com.aspose.pdf/fitrexplicitdestination/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitRExplicitDestination extends ExplicitDestination
```

表示显示页面的显式目标，其内容放大到足以在水平和垂直方向上完全适合由左、下、右和上坐标指定的矩形。如果所需的水平和垂直放大倍数不同，则使用两者中较小的一个，在另一个维度中将窗口内的矩形居中。任何参数的空值都可能导致不可预知的行为。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitRExplicitDestination(Page page, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | 创建实例并通过 DOM 页面对象和可见参数对其进行初始化。 |
| [FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | 创建远程显式目标。 |
| [FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-int-double-double-double-double-) | 创建远程显式目标。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | 获取可见矩形的底部垂直坐标。 |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | 获取可见矩形的左水平坐标。 |
| [getPage()](#getPage--) | 获取目标页面对象 |
| [getPageNumber()](#getPageNumber--) | 获取目标页码 |
| [getRight()](#getRight--) | 获取可见矩形的右横坐标。 |
| [getTop()](#getTop--) | 获取可见矩形的顶部垂直坐标。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 将对象状态转换为字符串值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitRExplicitDestination(Page page, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
```
public FitRExplicitDestination(Page page, double left, double bottom, double right, double top)
```


创建实例并通过 DOM 页面对象和可见参数对其进行初始化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM 页面对象。 |
| left | double | 可见矩形的左水平坐标。 |
| bottom | double | 可见矩形的底部垂直坐标。 |
| right | double | 可见矩形的右水平坐标。 |
| top | double | 可见矩形的顶部垂直坐标。 |

### FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
```
public FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | 包含此对象的父文档。 |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 可见矩形的左水平坐标。 |
| bottom | double | 可见矩形的底部垂直坐标。 |
| right | double | 可见矩形的右水平坐标。 |
| top | double | 可见矩形的顶部垂直坐标。 |

### FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 可见矩形的左水平坐标。 |
| bottom | double | 可见矩形的底部垂直坐标。 |
| right | double | 可见矩形的右水平坐标。 |
| top | double | 可见矩形的顶部垂直坐标。 |

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
### getBottom() {#getBottom--}
```
public double getBottom()
```


获取可见矩形的底部垂直坐标。

**退货：**
双倍价值
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


获取可见矩形的左水平坐标。

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
### getRight() {#getRight--}
```
public double getRight()
```


获取可见矩形的右横坐标。

**退货：**
双倍价值
### getTop() {#getTop--}
```
public double getTop()
```


获取可见矩形的顶部垂直坐标。

**退货：**
双倍价值
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


将对象状态转换为字符串值。示例：“1 FitR 100 200 300 400”。

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
