---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 {@code operators.m} 的类（移动到并开始新子路径）。"
type: docs
weight: 410
url: /zh/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

表示 {@code operators.m} 的类（移动到并开始新子路径）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | 初始化新的 {@code Operator.m}（移动到）运算符。 |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getX](#getX--) | X 坐标 |
| [getY](#getY--) | Y 坐标 |
| [setX](#setX-double-) | X 坐标 |
| [setY](#setY-double-) | Y 坐标 |
| [toString](#toString--) | 返回运算符的文本表示。 |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

初始化新的 {@code Operator.m}（移动到）运算符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | x 坐标。 |
| y |  | y 坐标。 |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getX {#getX--}
```
public double getX()
```

X 坐标

**Returns:**
double 值

### getY {#getY--}
```
public double getY()
```

Y 坐标

**Returns:**
double 值

### setX {#setX-double-}
```
public void setX(double value)
```

X 坐标

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setY {#setY-double-}
```
public void setY(double value)
```

Y 坐标

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
