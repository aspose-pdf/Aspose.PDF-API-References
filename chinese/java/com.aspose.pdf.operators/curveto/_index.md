---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 c 操作符的类（append curve to path）。"
type: docs
weight: 150
url: /zh/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

表示 c 操作符的类（append curve to path）。

## 字段

| 字段 | 描述 |
| --- | --- |
| [X1](#X1) | 获取或设置 X1 坐标。 |
| [X2](#X2) | 获取或设置 X2 坐标。 |
| [X3](#X3) | 获取或设置 X3 坐标。 |
| [Y1](#Y1) | 获取或设置 Y1 坐标。 |
| [Y2](#Y2) | 获取或设置 Y2 坐标。 |
| [Y3](#Y3) | 获取或设置 Y3 坐标。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | 初始化曲线操作符。 |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [toCommand](#toCommand--) | 仅供内部使用！ |
| [toString](#toString--) | 返回操作符的文本表示。 |

### X1 {#X1}
```
public double X1
```

获取或设置 X1 坐标。

### X2 {#X2}
```
public double X2
```

获取或设置 X2 坐标。

### X3 {#X3}
```
public double X3
```

获取或设置 X3 坐标。

### Y1 {#Y1}
```
public double Y1
```

获取或设置 Y1 坐标。

### Y2 {#Y2}
```
public double Y2
```

获取或设置 Y2 坐标。

### Y3 {#Y3}
```
public double Y3
```

获取或设置 Y3 坐标。

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

初始化曲线操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 |  | 第一点的横坐标。 |
| y1 |  | 第一点的纵坐标。 |
| x2 |  | 第二点的横坐标。 |
| y2 |  | 第二点的纵坐标。 |
| x3 |  | 第三点的横坐标。 |
| y3 |  | 第三点的纵坐标。 |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

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

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
