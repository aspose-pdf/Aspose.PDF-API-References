---
title: "Re"
linktitle: "Re"
second_title: "Aspose.PDF for Java API 参考"
description: "表示运算符 re 的类（向路径添加矩形）。"
type: docs
weight: 460
url: /zh/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

表示运算符 re 的类（向路径添加矩形）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Re](#Re--) | 提取目标的构造函数。 |
| [Re](#Re-double-double-double-double-) | 写入程序的构造函数。 |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | 提取目标的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getHeight](#getHeight--) | 矩形的高度。 |
| [getWidth](#getWidth--) | 获取矩形的宽度。 |
| [getX](#getX--) | 矩形最左侧的 X 坐标。 |
| [getY](#getY--) | 矩形底部的 Y 坐标。 |
| [setHeight](#setHeight-double-) | 矩形的高度。 |
| [setWidth](#setWidth-double-) | 设置矩形的宽度。 |
| [setX](#setX-double-) | 矩形最左侧的 X 坐标。 |
| [setY](#setY-double-) | 矩形底部的 Y 坐标。 |
| [toString](#toString--) | 返回运算符的文本表示。 |

### Re {#Re--}
```
public Re()
```

提取目标的构造函数。

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

写入程序的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | 矩形左下角的 X 坐标。 |
| y |  | 矩形左下角的 Y 坐标。 |
| 宽度 |  | 矩形的宽度。 |
| 高度 |  | 矩形的高度。 |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
提取目标的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getHeight {#getHeight--}
```
public double getHeight()
```

矩形的高度。

**Returns:**
矩形的高度。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取矩形的宽度。

**Returns:**
矩形的宽度。

### getX {#getX--}
```
public double getX()
```

矩形最左侧的 X 坐标。

**Returns:**
double 值

### getY {#getY--}
```
public double getY()
```

矩形底部的 Y 坐标。

**Returns:**
double 值

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

矩形的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 矩形的高度。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置矩形的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 矩形的宽度。 |

### setX {#setX-double-}
```
public void setX(double value)
```

矩形最左侧的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setY {#setY-double-}
```
public void setY(double value)
```

矩形底部的 Y 坐标。

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
