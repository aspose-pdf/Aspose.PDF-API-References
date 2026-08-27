---
title: "FitBExplicitDestination"
linktitle: "FitBExplicitDestination"
second_title: "Aspose.PDF for Java API 参考"
description: "表示显式目标，使页面的内容放大到恰好使其边界框完全适合窗口的水平和垂直方向。"
type: docs
weight: 1520
url: /zh/java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

表示显式目标，该目标显示页面并将其内容放大到恰好使其边界框完全适合窗口的水平和垂直方向。如果所需的水平和垂直放大因子不同，则使用较小的那个，并在另一个方向上将边界框居中于窗口。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | 创建远程显式目标。 |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | 创建远程显式目标。 |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | 通过 DOM 页面对象创建实例并进行初始化。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [toString](#toString--) | 将对象状态转换为字符串值。例如："1 FitB"。 |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
创建远程显式目标。

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

创建远程显式目标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 远程文档的目标页码。 |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
通过 DOM 页面对象创建实例并进行初始化。

### toString {#toString--}
```
public String toString()
```

将对象状态转换为字符串值。例如："1 FitB"。

**Returns:**
表示对象状态的字符串值。
