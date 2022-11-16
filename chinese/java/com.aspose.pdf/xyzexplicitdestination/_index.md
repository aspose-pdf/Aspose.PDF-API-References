---
title: XYZExplicitDestination
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示显示页面的显式目标，其坐标 left top 位于窗口的左上角，页面内容按 zoom 因子放大。
type: docs
weight: 411
url: /zh/java/com.aspose.pdf/xyzexplicitdestination/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class XYZExplicitDestination extends ExplicitDestination
```

表示显示页面的显式目标，该页面的坐标 (left, top) 位于窗口的左上角，页面内容放大了 zoom 倍数。任何参数 left、top 或 zoom 的空值指定该参数的当前值将保持不变。缩放值为 0 与空值具有相同的含义。

--------------------

文档 doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get\_Item(1).getDestination();左字符串 = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom();
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XYZExplicitDestination(Page page, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | 创建实例并通过 DOM 页面对象和可见参数对其进行初始化。 |
| [XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | 创建远程显式目标。 |
| [XYZExplicitDestination(int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-int-double-double-double-) | 创建远程显式目标。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(Page page, double left, double top, double zoom, boolean considerRotation)](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | 如果需要，考虑页面旋转，将目标创建到页面的指定位置。 |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | 创建 ExplicitDestination 子类的实例。 |
| [createDestinationToUpperLeftCorner(Page page)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | 创建指定页面的目的地。 |
| [createDestinationToUpperLeftCorner(Page page, double zoom)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | 创建目的地到指定页面的左上角。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | 获取窗口左上角的左侧水平坐标。 |
| [getPage()](#getPage--) | 获取目标页面对象 |
| [getPageNumber()](#getPageNumber--) | 获取目标页码 |
| [getTop()](#getTop--) | 获取窗口左上角的顶部垂直坐标。 |
| [getZoom()](#getZoom--) | 获取缩放因子。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 将对象状态转换为字符串值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XYZExplicitDestination(Page page, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
```
public XYZExplicitDestination(Page page, double left, double top, double zoom)
```


创建实例并通过 DOM 页面对象和可见参数对其进行初始化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM 页面对象。 |
| left | double | 窗口左上角的左水平坐标。 |
| top | double | 窗口左上角的顶部垂直坐标。 |
| zoom | double | 缩放系数。 |

### XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
```
public XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 包含此对象的父文档。 |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 窗口左上角的左水平坐标。 |
| top | double | 窗口左上角的顶部垂直坐标。 |
| zoom | double | 缩放系数。 |

### XYZExplicitDestination(int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```


创建远程显式目标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 远程文档的目标页码。 |
| left | double | 窗口左上角的左水平坐标。 |
| top | double | 窗口左上角的顶部垂直坐标。 |
| zoom | double | 缩放系数。 |

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
### createDestination(Page page, double left, double top, double zoom, boolean considerRotation) {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
```
public static XYZExplicitDestination createDestination(Page page, double left, double top, double zoom, boolean considerRotation)
```


如果需要，考虑页面旋转，将目标创建到页面的指定位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 目的地页面。 |
| left | double | 页面左侧位置。 |
| top | double | 页面顶部位置。 |
| zoom | double | 缩放因子（默认为 0）。 |
| considerRotation | boolean | 如果为真，位置将根据页面旋转重新计算。 |

**退货：**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - 目标对象。
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
### createDestinationToUpperLeftCorner(Page page) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page)
```


创建指定页面的目的地。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 目的地页面。 |

**退货：**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - 目标对象。
### createDestinationToUpperLeftCorner(Page page, double zoom) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page, double zoom)
```


创建目的地到指定页面的左上角。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 目的地页面。 |
| zoom | double | 缩放系数。 |

**退货：**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - 目标对象。
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


获取窗口左上角的左侧水平坐标。

**退货：**
双 - 双
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
### getTop() {#getTop--}
```
public double getTop()
```


获取窗口左上角的顶部垂直坐标。

**退货：**
双 - 双
### getZoom() {#getZoom--}
```
public double getZoom()
```


获取缩放因子。

**退货：**
双 - 双
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


将对象状态转换为字符串值。示例：“1 XYZ 100 200 3”。

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
