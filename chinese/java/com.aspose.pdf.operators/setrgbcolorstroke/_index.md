---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 RG 运算符的类（为描边运算符设置 RGB 颜色）。"
type: docs
weight: 720
url: /zh/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

表示 RG 运算符的类（为描边运算符设置 RGB 颜色）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | 使用颜色初始化操作符。 |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | 写入程序的构造函数。 |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | 操作符类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getB](#getB--) | 获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | 返回运算符指定的颜色。 |
| [getG](#getG--) | 获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。 |
| [getR](#getR--) | 获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。 |
| [setB](#setB-double-) | 获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。 |
| [setG](#setG-double-) | 获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。 |
| [setR](#setR-double-) | 获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。 |
| [toString](#toString--) | 返回操作符的文本表示。 |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
使用颜色初始化操作符。

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

写入程序的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r |  | 红色的水平从 0.0 到 1.0 |
| g |  | 绿色的水平从 0.0 到 1.0 |
| b |  | 蓝色的水平从 0.0 到 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
操作符类的构造函数。

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

### getB {#getB--}
```
public final double getB()
```

获取或设置蓝色分量。值：蓝色的水平，从 0.0 到 1.0。

**Returns:**
可做的值

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

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

### getR {#getR--}
```
public final double getR()
```

获取或设置红色分量。值：红色的水平，从 0.0 到 1.0。

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

### setG {#setG-double-}
```
public final void setG(double value)
```

获取或设置绿色分量。值：绿色的水平，从 0.0 到 1.0。

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

### toString {#toString--}
```
public String toString()
```

返回操作符的文本表示。

**Returns:**
运算符的文本表示。
