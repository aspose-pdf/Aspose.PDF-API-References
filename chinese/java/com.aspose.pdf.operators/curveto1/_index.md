---
title: "曲线到1"
linktitle: "曲线到1"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 v 操作符的类（append curve to path, initial point replicated）。"
type: docs
weight: 160
url: /zh/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

表示 v 操作符的类（append curve to path, initial point replicated）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | 初始化曲线操作符。 |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受操作符选择器。 |
| [getPoints](#getPoints--) | 曲线的点。 |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

初始化曲线操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x2 |  | 第二点的横坐标。 |
| y2 |  | 第二点的纵坐标。 |
| x3 |  | 第三点的横坐标。 |
| y3 |  | 第三点的纵坐标。 |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受操作符选择器。

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

曲线的点。

**Returns:**
Point 实例数组
