---
title: "SetDash"
linktitle: "SetDash"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 d 运算符的类（设置线段虚线模式）。"
type: docs
weight: 610
url: /zh/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

表示 d 运算符的类（设置线段虚线模式）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | 创建设置虚线模式的操作符。 |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getPattern](#getPattern--) | 虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。如果数组只有一个元素，则虚线和间隙的长度相等。 |
| [getPhase](#getPhase--) | 虚线相位。在开始描绘路径之前，需遍历虚线数组，累计虚线和间隙的长度。当累计长度等于虚线相位指定的值时，路径的描绘将开始，并且从此点起虚线数组将循环使用。 |
| [setPattern](#setPattern-int:A-) | 虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。如果数组只有一个元素，则虚线和间隙的长度相等。 |
| [setPhase](#setPhase-int-) | 虚线相位。在开始描绘路径之前，需遍历虚线数组，累计虚线和间隙的长度。当累计长度等于虚线相位指定的值时，路径的描绘将开始，并且从此点起虚线数组将循环使用。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 获取操作符的字符串表示。 |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

创建设置虚线模式的操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 模式 |  | 定义虚线模式的数组。 |
| 相位 |  | 虚线相位。 |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getPattern {#getPattern--}
```
public int[] getPattern()
```

虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。如果数组只有一个元素，则虚线和间隙的长度相等。

**Returns:**
int 数组

### getPhase {#getPhase--}
```
public int getPhase()
```

虚线相位。在开始描绘路径之前，需遍历虚线数组，累计虚线和间隙的长度。当累计长度等于虚线相位指定的值时，路径的描绘将开始，并且从此点起虚线数组将循环使用。

**Returns:**
int 值

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

虚线模式。数组的元素应为指定交替虚线和间隙长度的数字。如果数组只有一个元素，则虚线和间隙的长度相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 数组 |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

虚线相位。在开始描绘路径之前，需遍历虚线数组，累计虚线和间隙的长度。当累计长度等于虚线相位指定的值时，路径的描绘将开始，并且从此点起虚线数组将循环使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

仅供内部使用！

**Returns:**
ICommand 值 ICommand 对象

### toString {#toString--}
```
public String toString()
```

获取操作符的字符串表示。

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
