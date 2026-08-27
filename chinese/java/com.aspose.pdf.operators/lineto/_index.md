---
title: "LineTo"
linktitle: "LineTo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符 l 的类（向路径添加直线）。"
type: docs
weight: 380
url: /zh/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

表示运算符 l 的类（向路径添加直线）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LineTo](#LineTo-double-double-) | 初始化线操作符。 |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getX](#getX--) | 线点的 X 坐标。 |
| [getY](#getY--) | 线点的 Y 坐标。 |
| [setX](#setX-double-) | 线点的 X 坐标。 |
| [setY](#setY-double-) | 线点的 Y 坐标。 |
| [toString](#toString--) | 返回运算符的文本表示。 |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

初始化线操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | X 坐标。 |
| y |  | Y 坐标。 |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getX {#getX--}
```
public double getX()
```

线点的 X 坐标。

**Returns:**
double 值

### getY {#getY--}
```
public double getY()
```

线点的 Y 坐标。

**Returns:**
double 值

### setX {#setX-double-}
```
public void setX(double value)
```

线点的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setY {#setY-double-}
```
public void setY(double value)
```

线点的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toString {#toString--}
```
public String toString()
```

返回运算符的文本表示。

**Returns:**
操作符的文本表示。
