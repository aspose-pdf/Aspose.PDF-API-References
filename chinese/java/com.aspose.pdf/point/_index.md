---
title: "点"
linktitle: "点"
second_title: "Aspose.PDF for Java API 参考"
description: "表示具有分数坐标的点。"
type: docs
weight: 3870
url: /zh/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

表示具有分数坐标的点。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Point](#Point-double-double-) | 初始化 {@code Point} 的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | 计算两点之间的距离。 |
| [getTrivial](#getTrivial--) | 获取坐标全为零的点。 |
| [getX](#getX--) | 获取 X 坐标值。 |
| [getY](#getY--) | 获取 Y 坐标值。 |
| [setX](#setX-double-) | 设置 X 坐标值。 |
| [setY](#setY-double-) | 设置 Y 坐标值。 |
| [toPoint](#toPoint--) | 将点转换为 java.awt.geom.Point2D.Float 对象。 |
| [toString](#toString--) | 返回当前点的字符串表示。 |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

初始化 {@code Point} 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | x 坐标值。 |
| y |  | y 坐标值。 |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
计算两点之间的距离。

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

获取坐标全为零的点。

**Returns:**
点对象

### getX {#getX--}
```
public double getX()
```

获取 X 坐标值。

**Returns:**
double 值

### getY {#getY--}
```
public double getY()
```

获取 Y 坐标值。

**Returns:**
double 值

### setX {#setX-double-}
```
public void setX(double value)
```

设置 X 坐标值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setY {#setY-double-}
```
public void setY(double value)
```

设置 Y 坐标值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

将点转换为 java.awt.geom.Point2D.Float 对象。

**Returns:**
Float 结构。

### toString {#toString--}
```
public String toString()
```

返回当前点的字符串表示。

**Returns:**
字符串，表示当前点。
