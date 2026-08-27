---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符 Td 的类（移动文本位置）。"
type: docs
weight: 390
url: /zh/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

表示运算符 Td 的类（移动文本位置）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | 初始化操作符。 |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | 初始化操作符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getX](#getX--) | 文本位置的 X 坐标。 |
| [getY](#getY--) | 文本位置的 Y 坐标。 |
| [setX](#setX-double-) | 文本位置的 X 坐标。 |
| [setY](#setY-double-) | 文本位置的 Y 坐标。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

初始化操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | 文本位置的 X 坐标。 |
| y |  | 文本位置的 Y 坐标。 |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
初始化操作符。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getX {#getX--}
```
public double getX()
```

文本位置的 X 坐标。

**Returns:**
double 值

### getY {#getY--}
```
public double getY()
```

文本位置的 Y 坐标。

**Returns:**
double 值

### setX {#setX-double-}
```
public void setX(double value)
```

文本位置的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setY {#setY-double-}
```
public void setY(double value)
```

文本位置的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
