---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 SC 运算符的类，用于为描边颜色运算符设置颜色。"
type: docs
weight: 600
url: /zh/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

表示 SC 运算符的类，用于为描边颜色运算符设置颜色。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | 初始化操作符。 |
| [SetColorStroke](#SetColorStroke-double-) | 为 DeviceGray、CalGray 和 Indexed 颜色空间的描边操作符设置颜色。 |
| [SetColorStroke](#SetColorStroke-double:A-) | 允许设置颜色分量的构造函数。 |
| [SetColorStroke](#SetColorStroke-double-double-double-) | 为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边操作符设置颜色 |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | 为 CMYK 颜色空间的描边操作符设置颜色 |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | 初始化操作符。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getB](#getB--) | 获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。 |
| [getC](#getC--) | 获取或设置青色分量。 |
| [getColor](#getColor--) | 返回运算符指定的颜色。 |
| [getG](#getG--) | 获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。 |
| [getK](#getK--) | 获取或设置黑色分量。 |
| [getM](#getM--) | 获取或设置品红分量。 |
| [getR](#getR--) | 获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。 |
| [getY](#getY--) | 获取或设置黄色分量。 |
| [setB](#setB-double-) | 获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。 |
| [setC](#setC-double-) | 获取或设置青色分量。 |
| [setG](#setG-double-) | 获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。 |
| [setK](#setK-double-) | 获取或设置黑色分量。 |
| [setM](#setM-double-) | 获取或设置品红分量。 |
| [setR](#setR-double-) | 获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。 |
| [setY](#setY-double-) | 获取或设置黄色分量。 |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

初始化操作符。

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

为 DeviceGray、CalGray 和 Indexed 颜色空间的描边操作符设置颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g |  | 颜色值. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

允许设置颜色分量的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 |  | 颜色分量数组。 |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

为 DeviceRGB、CalRGB 和 Lab 颜色空间的描边操作符设置颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r |  | 红色分量。 |
| g |  | 绿色组件。 |
| b |  | 蓝色组件。 |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

为 CMYK 颜色空间的描边操作符设置颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c |  | 青色组件。 |
| m |  | 品红组件。 |
| y |  | 黄色组件。 |
| k |  | 黑色组件。 |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
初始化操作符。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getB {#getB--}
```
public final double getB()
```

获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。

**Returns:**
可做的值

### getC {#getC--}
```
public final double getC()
```

获取或设置青色分量。

**Returns:**
可做的值

### getColor {#getColor--}
```
public Color getColor()
```

返回运算符指定的颜色。

**Returns:**
运算符指定的颜色。

### getG {#getG--}
```
public final double getG()
```

获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。

**Returns:**
可做的值

### getK {#getK--}
```
public final double getK()
```

获取或设置黑色分量。

**Returns:**
可做的值

### getM {#getM--}
```
public final double getM()
```

获取或设置品红分量。

**Returns:**
可做的值

### getR {#getR--}
```
public final double getR()
```

获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。

**Returns:**
可做的值

### getY {#getY--}
```
public final double getY()
```

获取或设置黄色分量。

**Returns:**
可做的值

### setB {#setB-double-}
```
public final void setB(double value)
```

获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

### setC {#setC-double-}
```
public final void setC(double value)
```

获取或设置青色分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

### setG {#setG-double-}
```
public final void setG(double value)
```

获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setK {#setK-double-}
```
public final void setK(double value)
```

获取或设置黑色分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

### setM {#setM-double-}
```
public final void setM(double value)
```

获取或设置品红分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

### setR {#setR-double-}
```
public final void setR(double value)
```

获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

### setY {#setY-double-}
```
public final void setY(double value)
```

获取或设置黄色分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |
