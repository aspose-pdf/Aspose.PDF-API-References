---
title: "Dash"
linktitle: "Dash"
second_title: "Aspose.PDF for Java API 参考"
description: "表示线段虚线模式的类。"
type: docs
weight: 910
url: /zh/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

表示线段虚线模式的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Dash](#Dash-int:A-) | Dash 的构造函数。定义用于绘制虚线边框的破折号和间隙模式。 |
| [Dash](#Dash-int-int-) | Dash 的构造函数。定义使用指定的破折号和间隙的虚线边框，该破折号和间隙在整个虚线边框中保持不变。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOff](#getOff--) | 获取或设置第一个破折号之间间隙的长度。 |
| [getOn](#getOn--) | 获取或设置第一个破折号的长度。 |
| [getPattern](#getPattern--) | 获取定义用于绘制虚线边框的破折号和间隙模式的 dash 数组。 |
| [setOff](#setOff-int-) | 获取或设置第一个破折号之间间隙的长度。 |
| [setOn](#setOn-int-) | 获取或设置第一个破折号的长度。 |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Dash 的构造函数。定义用于绘制虚线边框的破折号和间隙模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 |  | 一个 dash 数组（至少两个值），定义用于绘制虚线边框的破折号和间隙模式。 |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Dash 的构造函数。定义使用指定的破折号和间隙的虚线边框，该破折号和间隙在整个虚线边框中保持不变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 开启 |  | 破折号的长度。 |
| 关闭 |  | 间隙的长度。 |

### getOff {#getOff--}
```
public final int getOff()
```

获取或设置第一个破折号之间间隙的长度。

**Returns:**
int 值

### getOn {#getOn--}
```
public final int getOn()
```

获取或设置第一个破折号的长度。

**Returns:**
int 值

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

获取定义用于绘制虚线边框的破折号和间隙模式的 dash 数组。

**Returns:**
int 数组

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

获取或设置第一个破折号之间间隙的长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

获取或设置第一个破折号的长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
