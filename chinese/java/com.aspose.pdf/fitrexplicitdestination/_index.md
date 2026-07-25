---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "表示显式目标，显示页面及其内容，放大程度恰好使左、下、右和上坐标指定的矩形完全适配。"
type: docs
weight: 1570
url: /zh/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

表示显式目标，该目标显示页面并将其内容放大到恰好使由坐标 left、bottom、right 和 top 指定的矩形在窗口中水平和垂直方向都完全适合。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将矩形居中于窗口。任何参数为 null 可能导致不可预测的行为。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | 创建远程显式目标。 |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | 创建远程显式目标。 |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | 创建实例并通过 DOM 页面对象和可见参数进行初始化。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBottom](#getBottom--) | 获取可见矩形的底部垂直坐标。 |
| [getLeft](#getLeft--) | 获取可见矩形的左侧水平坐标。 |
| [getRight](#getRight--) | 获取可见矩形的右侧水平坐标。 |
| [getTop](#getTop--) | 获取可见矩形的顶部垂直坐标。 |
| [toString](#toString--) | 将对象状态转换为字符串值。示例："1 FitR 100 200 300 400"。 |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
创建远程显式目标。

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |
| left |  | 可见矩形的左侧水平坐标。 |
| bottom |  | 可见矩形的底部垂直坐标。 |
| 右 |  | 可见矩形的右侧水平坐标。 |
| 顶部 |  | 可见矩形的顶部垂直坐标。 |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
创建实例并通过 DOM 页面对象和可见参数进行初始化。

### getBottom {#getBottom--}
```
public double getBottom()
```

获取可见矩形的底部垂直坐标。

**Returns:**
double 值

### getLeft {#getLeft--}
```
public double getLeft()
```

获取可见矩形的左侧水平坐标。

**Returns:**
double 值

### getRight {#getRight--}
```
public double getRight()
```

获取可见矩形的右侧水平坐标。

**Returns:**
double 值

### getTop {#getTop--}
```
public double getTop()
```

获取可见矩形的顶部垂直坐标。

**Returns:**
double 值

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。示例："1 FitR 100 200 300 400"。

**Returns:**
表示对象状态的字符串值。
