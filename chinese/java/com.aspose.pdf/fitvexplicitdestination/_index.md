---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "表示显式目标，该目标在窗口左边缘显示页面，水平坐标 left 位于左侧，并且页面内容被适当放大。"
type: docs
weight: 1580
url: /zh/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

表示显式目标，该目标显示页面，并将水平坐标 left 定位在窗口的左侧边缘，页面内容放大到恰好使页面的整个高度适合窗口。left 为 null 时表示保留该参数的当前值不变。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | 创建远程显式目标。 |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | 创建远程显式目标。 |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | 创建实例并通过 DOM 页面对象和 left 参数进行初始化。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLeft](#getLeft--) | 获取水平坐标 left，位于窗口左边缘。 |
| [toString](#toString--) | 将对象状态转换为字符串值。例如："1 FitV 100"。 |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
创建远程显式目标。

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |
| left |  | 水平坐标 left 位于窗口左边缘。 |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
创建实例并通过 DOM 页面对象和 left 参数进行初始化。

### getLeft {#getLeft--}
```
public double getLeft()
```

获取水平坐标 left，位于窗口左边缘。

**Returns:**
double 值

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。例如："1 FitV 100"。

**Returns:**
表示对象状态的字符串值。
