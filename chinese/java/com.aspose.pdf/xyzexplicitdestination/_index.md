---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示显式目标，该目标在窗口左上角显示页面，坐标 (left, top) 定位，并显示页面内容。"
type: docs
weight: 5800
url: /zh/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> 表示显式目标，该目标在窗口左上角显示页面，坐标 (left, top) 位于窗口左上角，页面内容按 zoom 因子放大。对于参数 left、top 或 zoom 的任意一个为 null 值，表示该参数的当前值保持不变。zoom 为 0 的含义与 null 值相同。 </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | 创建远程显式目标。 |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | 创建远程显式目标。 |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | 创建实例并通过 DOM 页面对象和可见参数进行初始化。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | 创建目标到页面的指定位置，必要时考虑页面旋转。 |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | 创建目标到指定页面。 |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | 创建目标到指定页面的左上角。 |
| [getLeft](#getLeft--) | 获取窗口左上角的左水平坐标。 |
| [getTop](#getTop--) | 获取窗口左上角的顶部垂直坐标。 |
| [getZoom](#getZoom--) | 获取缩放因子。 |
| [toString](#toString--) | 将对象状态转换为字符串值。示例："1 XYZ 100 200 3"。 |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
创建远程显式目标。

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |
| left |  | 窗口左上角的左水平坐标。 |
| 顶部 |  | 窗口左上角的顶部垂直坐标。 |
| 缩放 |  | 缩放因子。 |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
创建实例并通过 DOM 页面对象和可见参数进行初始化。

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
创建目标到页面的指定位置，必要时考虑页面旋转。

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
创建目标到指定页面。

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
创建目标到指定页面的左上角。

### getLeft {#getLeft--}
```
public double getLeft()
```

获取窗口左上角的左水平坐标。

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

获取窗口左上角的顶部垂直坐标。

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

获取缩放因子。

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。示例："1 XYZ 100 200 3"。

**Returns:**
表示对象状态的字符串值。
