---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 y 操作符的类（append curve to path, final point replicated）。"
type: docs
weight: 170
url: /zh/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

表示 y 操作符的类（append curve to path, final point replicated）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | 初始化曲线操作符。 |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getPoints](#getPoints--) | 曲线的点。 |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

初始化曲线操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 |  | 第二点的横坐标。 |
| y1 |  | 第二点的纵坐标。 |
| x3 |  | 第三点的横坐标。 |
| y3 |  | 第三点的纵坐标。 |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

曲线的点。

**Returns:**
Point 实例数组
