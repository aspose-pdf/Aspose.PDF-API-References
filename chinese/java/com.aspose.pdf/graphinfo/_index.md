---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图形信息。"
type: docs
weight: 1840
url: /zh/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

表示图形信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆图形信息。 |
| [getColor](#getColor--) | 获取一个 {@code Color} 对象，指示图形的颜色。 |
| [getDashArray](#getDashArray--) | 获取虚线数组。 |
| [getDashPhase](#getDashPhase--) | 获取虚线相位。 |
| [getFillColor](#getFillColor--) | 获取一个 {@code Color} 对象，表示图形的填充颜色。 |
| [getLineWidth](#getLineWidth--) | 获取一个 float 值，表示图形的线宽。 |
| [getRotationAngle](#getRotationAngle--) | 获取一个 float 值，表示在转换坐标系时坐标系的旋转角度。 |
| [getScalingRateX](#getScalingRateX--) | 获取一个 float 值，表示在转换坐标系时 x 坐标的缩放比例。 |
| [getScalingRateY](#getScalingRateY--) | 获取一个 float 值，表示在转换坐标系时 y 坐标的缩放比例。 |
| [getSkewAngleX](#getSkewAngleX--) | 获取一个 float 值，表示在转换坐标系时 x 坐标的倾斜角度。 |
| [getSkewAngleY](#getSkewAngleY--) | 获取一个 float 值，表示在转换坐标系时 y 坐标的倾斜角度。 |
| [getX](#getX--) | 在使用 TableAbsorber 时检索垂直边界的 X 坐标，对水平边界返回 "-1"。 |
| [getY](#getY--) | 在使用 TableAbsorber 时检索水平边界的 Y 坐标，对垂直边界返回 "-1"。 |
| [isDoubled](#isDoubled--) | 获取边框是否加倍。 |
| [setColor](#setColor-com.aspose.pdf.Color-) | 设置一个 {@code Color} 对象，表示图形的颜色。 |
| [setDashArray](#setDashArray-int:A-) | 设置虚线数组。 |
| [setDashPhase](#setDashPhase-int-) | 设置虚线相位。 |
| [setDoubled](#setDoubled-boolean-) | 设置边框是否加倍。 |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | 设置一个 {@code Color} 对象，表示图形的填充颜色。 |
| [setLineWidth](#setLineWidth-float-) | 设置一个 float 值，表示图形的线宽。 |
| [setRotationAngle](#setRotationAngle-double-) | 设置一个 float 值，表示在转换坐标系时坐标系的旋转角度。 |
| [setScalingRateX](#setScalingRateX-double-) | 设置一个 float 值，表示在转换坐标系时 x 坐标的缩放比例。 |
| [setScalingRateY](#setScalingRateY-double-) | 设置一个 float 值，表示在转换坐标系时 y 坐标的缩放比例。 |
| [setSkewAngleX](#setSkewAngleX-double-) | 设置一个 float 值，表示在转换坐标系时 x 坐标的倾斜角度。 |
| [setSkewAngleY](#setSkewAngleY-double-) | 设置一个 float 值，表示在转换坐标系时 y 坐标的倾斜角度。 |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆图形信息。

**Returns:**
克隆的对象。

### getColor {#getColor--}
```
public Color getColor()
```

获取一个 {@code Color} 对象，指示图形的颜色。

**Returns:**
表示颜色的对象

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

获取虚线数组。

**Returns:**
虚线数组

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

获取虚线相位。

**Returns:**
虚线相位。

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

获取一个 {@code Color} 对象，表示图形的填充颜色。

**Returns:**
指示填充颜色的对象

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

获取一个 float 值，表示图形的线宽。

**Returns:**
指示线宽的值。

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

获取一个 float 值，表示在转换坐标系时坐标系的旋转角度。

**Returns:**
double 值

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

获取一个 float 值，表示在转换坐标系时 x 坐标的缩放比例。

**Returns:**
double 值

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

获取一个 float 值，表示在转换坐标系时 y 坐标的缩放比例。

**Returns:**
double 值

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

获取一个 float 值，表示在转换坐标系时 x 坐标的倾斜角度。

**Returns:**
double 值

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

获取一个 float 值，表示在转换坐标系时 y 坐标的倾斜角度。

**Returns:**
double 值

### getX {#getX--}
```
public final double getX()
```

在使用 TableAbsorber 时检索垂直边界的 X 坐标，对水平边界返回 "-1"。

**Returns:**
double 值

### getY {#getY--}
```
public final double getY()
```

在使用 TableAbsorber 时检索水平边界的 Y 坐标，对垂直边界返回 "-1"。

**Returns:**
double 值

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

获取边框是否加倍。

**Returns:**
布尔值

### setColor {#setColor-com.aspose.pdf.Color-}
设置一个 {@code Color} 对象，表示图形的颜色。

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

设置虚线数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 虚线数组 |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

设置虚线相位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 虚线相位。 |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

设置边框是否加倍。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
设置一个 {@code Color} 对象，表示图形的填充颜色。

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

设置一个 float 值，表示图形的线宽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示线宽的值。 |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

设置一个 float 值，表示在转换坐标系时坐标系的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

设置一个 float 值，表示在转换坐标系时 x 坐标的缩放比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

设置一个 float 值，表示在转换坐标系时 y 坐标的缩放比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

设置一个 float 值，表示在转换坐标系时 x 坐标的倾斜角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

设置一个 float 值，表示在转换坐标系时 y 坐标的倾斜角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
