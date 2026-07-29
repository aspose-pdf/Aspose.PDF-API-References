---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF for Java API 参考"
description: "表示矩形的类。"
type: docs
weight: 4100
url: /zh/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

表示矩形的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Rectangle 的构造函数。 |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Rectangle 的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | 相交矩形。已废弃的方法。请改用 Intersect。 |
| [center](#center--) | 返回矩形中心的坐标。 |
| [clone](#clone--) | 克隆 Rectangle 对象。 |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | 确定给定点是否在矩形内部。 |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | 确定给定点是否在矩形内部。 |
| [containsLine](#containsLine-double-double-double-double-) | 确定矩形是否包含由两点表示的直线。 |
| [containsPoint](#containsPoint-double-double-) | 确定给定点是否位于矩形内部。 |
| [deepClone](#deepClone--) | 克隆 Rectangle 对象。 |
| [equals](#equals-java.lang.Object-) | 检查矩形是否相等，即具有相同的位置和大小。 |
| [fromRect](#fromRect-java.awt.Rectangle-) | 从给定的 System.Drawing.Rectangle 实例初始化新矩形。 |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | 从给定的 System.Drawing.Rectangle 实例初始化新矩形。 |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | 计算矩形的面积。 |
| [getEmpty](#getEmpty--) | 获取空矩形 |
| [getHeight](#getHeight--) | 获取矩形的高度。 |
| [getLLX](#getLLX--) | 获取左下角的 X 坐标。 |
| [getLLY](#getLLY--) | 获取左下角的 Y 坐标。 |
| [getTrivial](#getTrivial--) | 初始化平凡矩形，即位置和大小均为零的矩形。 |
| [getURX](#getURX--) | 获取右上角的 X 坐标。 |
| [getURY](#getURY--) | 获取右上角的 Y 坐标。 |
| [getWidth](#getWidth--) | 获取矩形的宽度。 |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。） |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | 矩形相交。 |
| [isEmpty](#isEmpty--) | 检查矩形是否为空。 |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | 检查此矩形是否完全包含另一个矩形。即整个另一个矩形位于此矩形内部。与 IsIntersect 方法的区别在于，IsIntersect 对部分相交的矩形返回 true，而 IsInclude 则返回 false。 |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | 确定此矩形是否与另一个矩形相交。 |
| [isPoint](#isPoint--) | 检查矩形是否为点，即 LLX 等于 URX 且 LLY 等于 URY。 |
| [isTrivial](#isTrivial--) | 检查矩形是否为平凡矩形，即大小和位置均为零。 |
| [join](#join-com.aspose.pdf.Rectangle-) | 合并矩形。 |
| [moveBy](#moveBy-double-double-) | 按指定的增量平移矩形。 |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | 检查矩形是否近似相等，即位置和大小在（误差 delta）范围内基本相同。 |
| [parse](#parse-java.lang.String-) | 尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。 |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | 按指定角度旋转矩形。 |
| [rotateAngle](#rotateAngle-int-) | 按指定角度旋转矩形。 |
| [setLLX](#setLLX-double-) | 设置左下角的 X 坐标。 |
| [setLLY](#setLLY-double-) | 设置左下角的 Y 坐标。 |
| [setURX](#setURX-double-) | 设置右上角的 X 坐标。 |
| [setURY](#setURY-double-) | 设置右上角的 Y 坐标。 |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | 将矩形转换为点数组（"QuadPoints"）。 |
| [toRect](#toRect--) | 将矩形转换为 System.Drawing.Rectangle 的实例。浮点位置和尺寸会被截断。 |
| [toString](#toString--) | 获取矩形的字符串表示。 |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Rectangle 的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| llx |  | 左下角的 X。 |
| lly |  | 左下角的 Y。 |
| urx |  | 右上角的 X。 |
| ury |  | 右上角的 Y。 |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Rectangle 的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| llx |  | 左下角的 X。 |
| lly |  | 左下角的 Y。 |
| urx |  | 右上角的 X。 |
| ury |  | 右上角的 Y。 |
| normalizeCoordinates |  | 规范化矩形的坐标。 |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
相交矩形。已废弃的方法。请改用 Intersect。

### center {#center--}
```
public Point center()
```

返回矩形中心的坐标。

**Returns:**
矩形中心点。

### clone {#clone--}
```
public Rectangle clone()
```

克隆 Rectangle 对象。

**Returns:**
克隆对象。

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
确定给定点是否在矩形内部。

### contains {#contains-com.aspose.pdf.Point-boolean-}
确定给定点是否在矩形内部。

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

确定矩形是否包含由两点表示的直线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 |  | 线段起点的 X 坐标。 |
| y1 |  | 线段起点的 Y 坐标。 |
| x2 |  | 线段终点的 X 坐标。 |
| y2 |  | 线段终点的 Y 坐标。 |

**Returns:**
{@code true} 如果矩形包含该线段；否则，{@code false}。

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

确定给定点是否位于矩形内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | 点的 X 坐标。 |
| y |  | 点的 Y 坐标。 |

**Returns:**
{@code true} 如果点位于矩形内部；否则，{@code false}。

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

克隆 Rectangle 对象。

**Returns:**
克隆对象。

### equals {#equals-java.lang.Object-}
检查矩形是否相等，即具有相同的位置和大小。

### fromRect {#fromRect-java.awt.Rectangle-}
从给定的 System.Drawing.Rectangle 实例初始化新矩形。

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
从给定的 System.Drawing.Rectangle 实例初始化新矩形。

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

计算矩形的面积。

**Returns:**
矩形的面积（double），通过宽度与高度相乘计算得到。

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

获取空矩形

**Returns:**
新的 Rectangle 对象

### getHeight {#getHeight--}
```
public double getHeight()
```

获取矩形的高度。

**Returns:**
double 值

### getLLX {#getLLX--}
```
public double getLLX()
```

获取左下角的 X 坐标。

**Returns:**
double 值

### getLLY {#getLLY--}
```
public double getLLY()
```

获取左下角的 Y 坐标。

**Returns:**
double 值

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

初始化平凡矩形，即位置和大小均为零的矩形。

**Returns:**
新的 Rectangle 对象

### getURX {#getURX--}
```
public double getURX()
```

获取右上角的 X 坐标。

**Returns:**
double 值

### getURY {#getURY--}
```
public double getURY()
```

获取右上角的 Y 坐标。

**Returns:**
double 值

### getWidth {#getWidth--}
```
public double getWidth()
```

获取矩形的宽度。

**Returns:**
double 值

### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。）

**Returns:**
此对象的哈希码值。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
矩形相交。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

检查矩形是否为空。

**Returns:**
布尔值

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
检查此矩形是否完全包含另一个矩形。即整个另一个矩形位于此矩形内部。与 IsIntersect 方法的区别在于，IsIntersect 对部分相交的矩形返回 true，而 IsInclude 则返回 false。

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
确定此矩形是否与另一个矩形相交。

### isPoint {#isPoint--}
```
public boolean isPoint()
```

检查矩形是否为点，即 LLX 等于 URX 且 LLY 等于 URY。

**Returns:**
布尔值

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

检查矩形是否为平凡矩形，即大小和位置均为零。

**Returns:**
布尔值

### join {#join-com.aspose.pdf.Rectangle-}
合并矩形。

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

按指定的增量平移矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx |  | 沿 X 轴的位移值。 |
| dy |  | 沿 Y 轴的位移值。 |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
检查矩形是否近似相等，即位置和大小在（误差 delta）范围内基本相同。

### parse {#parse-java.lang.String-}
尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。

### rotate {#rotate-com.aspose.pdf.Rotation-}
按指定角度旋转矩形。

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

按指定角度旋转矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle |  | 旋转角度（度），范围在 0 到 360 之间。 |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

设置左下角的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

设置左下角的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

设置右上角的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

设置右上角的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

将矩形转换为点数组（"QuadPoints"）。

**Returns:**
点数组。

### toRect {#toRect--}
```
public Rectangle toRect()
```

将矩形转换为 System.Drawing.Rectangle 的实例。浮点位置和尺寸会被截断。

**Returns:**
转换结果。

### toString {#toString--}
```
public String toString()
```

获取矩形的字符串表示。

**Returns:**
字符串的格式为 llx,lly,urx,ury。
