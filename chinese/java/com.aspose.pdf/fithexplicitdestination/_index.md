---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "表示显式目标，显示页面时将垂直坐标 top 定位在窗口的顶部边缘，并且页面内容恰好被放大。"
type: docs
weight: 1560
url: /zh/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

表示显式目标，该目标显示页面，并将垂直坐标 top 定位在窗口的顶部边缘，页面内容放大到恰好使页面的整个宽度适合窗口。top 为 null 时表示保留该参数的当前值不变。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | 创建远程显式目标。 |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | 创建远程显式目标。 |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | 创建实例并通过 DOM 页面对象和 top 参数进行初始化。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTop](#getTop--) | 获取位于窗口顶部边缘的垂直坐标 top。 |
| [toString](#toString--) | 将对象状态转换为字符串值。例如："1 FitH 100"。 |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
创建远程显式目标。

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |
| 顶部 |  | 位于窗口顶部边缘的垂直坐标 top。 |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
创建实例并通过 DOM 页面对象和 top 参数进行初始化。

### getTop {#getTop--}
```
public double getTop()
```

获取位于窗口顶部边缘的垂直坐标 top。

**Returns:**
double 值

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。例如："1 FitH 100"。

**Returns:**
表示对象状态的字符串值。
