---
title: "弧"
linktitle: "弧"
second_title: "Aspose.PDF for Java API 参考"
description: "表示弧线。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

表示弧线。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Arc](#Arc--) | 仅供内部使用 |
| [Arc](#Arc-double-double-double-double-double-) | 初始化 {@code Arc} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getAlpha](#getAlpha--) | 获取指示弧起始角度的 float 值。 |
| [getBeta](#getBeta--) | 获取指示弧结束角度的 float 值。 |
| [getPosX](#getPosX--) | 获取指示弧线中心 x 坐标的浮点值。 |
| [getPosY](#getPosY--) | 获取指示弧线中心 y 坐标的浮点值。 |
| [getRadius](#getRadius--) | 获取指示弧半径的 float 值。 |
| [setAlpha](#setAlpha-double-) | 设置指示弧起始角度的 float 值。 |
| [setBeta](#setBeta-double-) | 设置指示弧结束角度的 float 值。 |
| [setPosX](#setPosX-double-) | 设置指示弧线中心 x 坐标的浮点值。 |
| [setPosY](#setPosY-double-) | 设置指示弧线中心 y 坐标的浮点值。 |
| [setRadius](#setRadius-double-) | 设置指示弧半径的 float 值。 |

### Arc {#Arc--}
```
public Arc()
```

仅供内部使用

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

初始化 {@code Arc} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| posX |  | 弧的中心点的 x 坐标。 |
| posY |  | 弧的中心点的 y 坐标。 |
| 半径 |  | 弧的半径值。 |
| alpha |  | 弧的起始角度值。 |
| beta |  | 弧的结束角度值。 |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

检查该项是否适合给定容器尺寸（包括边界）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
如果匹配则为 true；否则为 false。

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

获取指示弧起始角度的 float 值。

**Returns:**
alpha 值。

### getBeta {#getBeta--}
```
public double getBeta()
```

获取指示弧结束角度的 float 值。

**Returns:**
beta 值

### getPosX {#getPosX--}
```
public double getPosX()
```

获取指示弧线中心 x 坐标的浮点值。

**Returns:**
弧的中心的 x 坐标。

### getPosY {#getPosY--}
```
public double getPosY()
```

获取指示弧线中心 y 坐标的浮点值。

**Returns:**
弧的中心的 y 坐标。

### getRadius {#getRadius--}
```
public double getRadius()
```

获取指示弧半径的 float 值。

**Returns:**
指示弧半径的值。

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

设置指示弧起始角度的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | alpha 值。 |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

设置指示弧结束角度的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | beta 值 |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

设置指示弧线中心 x 坐标的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 弧的中心的 x 坐标。 |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

设置指示弧线中心 y 坐标的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 弧的中心的 y 坐标。 |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

设置指示弧半径的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示弧半径的。 |
