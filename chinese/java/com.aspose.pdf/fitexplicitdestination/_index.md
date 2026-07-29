---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "表示显式目标，该目标显示页面及其内容，放大到恰好在窗口中水平和垂直方向上完整显示整页。如果"
type: docs
weight: 1550
url: /zh/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

表示显式目标，该目标显示页面并将其内容放大到恰好使整个页面在窗口中水平和垂直方向都完全适合。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将页面居中于窗口。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | 创建远程显式目标。 |
| [FitExplicitDestination](#FitExplicitDestination-int-) | 创建远程显式目标。 |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | 创建本地显式目标。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [toString](#toString--) | 将对象状态转换为字符串值。例如："1 Fit"。 |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
创建远程显式目标。

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
创建本地显式目标。

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。例如："1 Fit"。

**Returns:**
表示对象状态的字符串值。
