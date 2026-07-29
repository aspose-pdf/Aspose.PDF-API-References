---
title: "设置CMYK颜色"
linktitle: "设置CMYK颜色"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 k 运算符的类（为非描边操作设置 CMYK 颜色）。"
type: docs
weight: 530
url: /zh/java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColor

```
public class SetCMYKColor extends SetColorOperator
```

表示 k 运算符的类（为非描边操作设置 CMYK 颜色）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SetCMYKColor](#SetCMYKColor-double-double-double-double-) | 初始化操作符。 |
| [SetCMYKColor](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | 接受访问者对象以处理操作符。 |
| [getC](#getC--) | 获取或设置青色分量。 |
| [getColor](#getColor--) | 返回颜色。 |
| [getK](#getK--) | 获取或设置黑色分量。 |
| [getM](#getM--) | 获取或设置品红分量。 |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | 获取或设置黄色分量。 |
| [setC](#setC-double-) | 获取或设置青色分量。 |
| [setK](#setK-double-) | 获取或设置黑色分量。 |
| [setM](#setM-double-) | 获取或设置品红分量。 |
| [setY](#setY-double-) | 获取或设置黄色分量。 |

### SetCMYKColor {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```

初始化操作符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c |  | 青色的水平从0.0到1.0 |
| m |  | 品红的水平从0.0到1.0 |
| y |  | 黄色的水平从0.0到1.0 |
| k |  | 黑色的水平从0.0到1.0 |

### SetCMYKColor {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
接受访问者对象以处理操作符。

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

返回颜色。

**Returns:**
运算符指定的颜色。

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

获取或设置黄色分量。

**Returns:**
可做的值

### setC {#setC-double-}
```
public final void setC(double value)
```

获取或设置青色分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |

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

### setY {#setY-double-}
```
public final void setY(double value)
```

获取或设置黄色分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 可做的值 |
