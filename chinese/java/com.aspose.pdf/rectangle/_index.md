---
title: Rectangle
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类代表矩形。
type: docs
weight: 300
url: /zh/java/com.aspose.pdf/rectangle/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Comparable、java.lang.Cloneable
```
public final class Rectangle implements Comparable<Object>, Cloneable
```

类代表矩形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle(double llx, double lly, double urx, double ury)](#Rectangle-double-double-double-double-) | 矩形的构造函数。 |
| [Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)](#Rectangle-double-double-double-double-boolean-) | 矩形的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [_Intersect(Rectangle otherRect)](#-Intersect-com.aspose.pdf.Rectangle-) | 与矩形相交。 |
| [center()](#center--) | 返回矩形中心的坐标。 |
| [clone()](#clone--) | 克隆矩形对象。 |
| [compareTo(Object arg0)](#compareTo-java.lang.Object-) | 相比于 |
| [contains(Point point)](#contains-com.aspose.pdf.Point-) | 确定给定点是否在矩形内部。 |
| [deepClone()](#deepClone--) | 克隆矩形对象。 |
| [equals(Object other)](#equals-java.lang.Object-) | 检查矩形是否相等，即具有相同的位置和大小。 |
| [fromRect(Rectangle src)](#fromRect-java.awt.Rectangle-) | 从 System.Drawing.Rectangle 的给定实例初始化新矩形。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取空矩形 |
| [getHeight()](#getHeight--) | 获取矩形的高度。 |
| [getLLX()](#getLLX--) | 获取左下角的 X 坐标。 |
| [getLLY()](#getLLY--) | 获取 Y - 左下角的坐标。 |
| [getTrivial()](#getTrivial--) | 初始化普通矩形，即位置和大小为零的矩形。 |
| [getURX()](#getURX--) | 获取 X - 右上角的坐标。 |
| [getURY()](#getURY--) | 获取 Y - 右上角的坐标。 |
| [getWidth()](#getWidth--) | 获取矩形的宽度。 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [intersect(Rectangle otherRect)](#intersect-com.aspose.pdf.Rectangle-) | 与矩形相交。 |
| [isEmpty()](#isEmpty--) | 检查矩形是否为空。 |
| [isInclude(Rectangle otherRect, double rotationAngle)](#isInclude-com.aspose.pdf.Rectangle-double-) | 检查此矩形是否包含整个另一个矩形。 |
| [isIntersect(Rectangle otherRect)](#isIntersect-com.aspose.pdf.Rectangle-) | 确定此矩形是否与其他矩形相交。 |
| [isPoint()](#isPoint--) | 检查矩形是否为点，即 |
| [isTrivial()](#isTrivial--) | 检查矩形是否平凡，即大小和位置为零。 |
| [join(Rectangle otherRect)](#join-com.aspose.pdf.Rectangle-) | 连接矩形。 |
| [nearEquals(Rectangle other, double delta)](#nearEquals-com.aspose.pdf.Rectangle-double-) | 检查矩形是否接近相等，即具有接近相同（最多为增量）的位置和大小。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String value)](#parse-java.lang.String-) | 尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。 |
| [rotate(int angle)](#rotate-int-) | 按指定角度旋转矩形。 |
| [rotateAngle(int angle)](#rotateAngle-int-) | 按指定角度旋转矩形。 |
| [setLLX(double value)](#setLLX-double-) | 设置左下角的 X 坐标。 |
| [setLLY(double value)](#setLLY-double-) | 设置 Y - 左下角的坐标。 |
| [setURX(double value)](#setURX-double-) | 设置 X - 右上角的坐标。 |
| [setURY(double value)](#setURY-double-) | 设置 Y - 右上角的坐标。 |
| [toArray(ITrailerable trailerable)](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints()](#toPoints--) | 将矩形转换为点数组（“QuadPoints”）。 |
| [toRect()](#toRect--) | 将矩形转换为 System.Drawing.Rectangle 的实例。 |
| [toString()](#toString--) | 获取矩形字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle(double llx, double lly, double urx, double ury) {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```


矩形的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| llx | double | 左下角的X。 |
| lly | double | 左下角的Y。 |
| urx | double | 右上角的X。 |
| ury | double | 右上角的Y。 |

### Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates) {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```


矩形的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| llx | double | 左下角的X。 |
| lly | double | 左下角的Y。 |
| urx | double | 右上角的X。 |
| ury | double | 右上角的Y。 |
| normalizeCoordinates | boolean | 归一化矩形的坐标。 |

### _Intersect(Rectangle otherRect) {#-Intersect-com.aspose.pdf.Rectangle-}
```
public void _Intersect(Rectangle otherRect)
```


与矩形相交。过时的方法。请改用相交。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### center() {#center--}
```
public Point center()
```


返回矩形中心的坐标。

**退货：**
[Point](../../com.aspose.pdf/point) - 位于矩形中心的点。
### clone() {#clone--}
```
public Object clone()
```


克隆矩形对象。

**退货：**
java.lang.Object - 克隆对象。
### compareTo(Object arg0) {#compareTo-java.lang.Object-}
```
public int compareTo(Object arg0)
```


相比于

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object | 比较对象 |

**退货：**
int - 整数值
### contains(Point point) {#contains-com.aspose.pdf.Point-}
```
public boolean contains(Point point)
```


确定给定点是否在矩形内部。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | 指向检查。 |

**退货：**
boolean - 如果点在 recatngle 内则为真。
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆矩形对象。

**退货：**
java.lang.Object - 克隆对象。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


检查矩形是否相等，即具有相同的位置和大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | java.lang.Object | 将被比较的矩形。 |

**退货：**
boolean - 如果矩形相等则为 True，否则为 false。
### fromRect(Rectangle src) {#fromRect-java.awt.Rectangle-}
```
public static Rectangle fromRect(Rectangle src)
```


从 System.Drawing.Rectangle 的给定实例初始化新矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.awt.Rectangle | 位置和大小将设置为新矩形的源矩形。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 新矩形。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


获取空矩形

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 新的矩形对象
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取矩形的高度。

**退货：**
双倍价值
### getLLX() {#getLLX--}
```
public double getLLX()
```


获取左下角的 X 坐标。

**退货：**
双倍价值
### getLLY() {#getLLY--}
```
public double getLLY()
```


获取 Y - 左下角的坐标。

**退货：**
双倍价值
### getTrivial() {#getTrivial--}
```
public static Rectangle getTrivial()
```


初始化普通矩形，即位置和大小为零的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 新的矩形对象
### getURX() {#getURX--}
```
public double getURX()
```


获取 X - 右上角的坐标。

**退货：**
双倍价值
### getURY() {#getURY--}
```
public double getURY()
```


获取 Y - 右上角的坐标。

**退货：**
双倍价值
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取矩形的宽度。

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码值。支持此方法是为了散列表的好处，例如 java.util.HashMap 提供的散列表。

hashCode的一般契约是：

 *  每当在 Java 应用程序的执行期间对同一对象多次调用它时，hashCode 方法必须一致地返回相同的整数，前提是在对象的 equals 比较中使用的信息没有被修改。从一个应用程序的一次执行到同一应用程序的另一次执行，该整数不需要保持一致。
 *  如果根据 equals(Object) 方法两个对象相等，则对这两个对象中的每一个调用 hashCode 方法必须产生相同的整数结果。
 *  这是*not*要求如果两个对象根据 java.lang.Object 不相等\#equals(java.lang.Object).equals(java.lang.Object) 方法，然后在两个对象中的每一个上调用 hashCode 方法必须产生不同的整数结果。但是，程序员应该知道，为不相等的对象生成不同的整数结果可能会提高哈希表的性能。

在相当实用的情况下，类 Object 定义的 hashCode 方法确实会为不同的对象返回不同的整数。 （这通常是通过将对象的内部地址转换为整数来实现的，但 JavaTM 编程语言不需要这种实现技术。）

**退货：**
int - 此对象的哈希码值。
### intersect(Rectangle otherRect) {#intersect-com.aspose.pdf.Rectangle-}
```
public Rectangle intersect(Rectangle otherRect)
```


与矩形相交。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | 与此矩形相交的矩形。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形的交集；如果矩形不相交，则为 null。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


检查矩形是否为空。

**退货：**
boolean - 布尔值
### isInclude(Rectangle otherRect, double rotationAngle) {#isInclude-com.aspose.pdf.Rectangle-double-}
```
public boolean isInclude(Rectangle otherRect, double rotationAngle)
```


检查此矩形是否包含整个另一个矩形。即整个另一个矩形在这个矩形内。与 IsIntersect 方法的不同之处在于，IsIntersect 对部分相交的矩形为真，但 IsInclude 为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | 选中包含的矩形。 |
| rotationAngle | double | 另一个矩形的旋转角度（以弧度为单位）。 |

**退货：**
boolean - 如果此矩形包含整个指定的矩形，则为 True。否则为假。
### isIntersect(Rectangle otherRect) {#isIntersect-com.aspose.pdf.Rectangle-}
```
public boolean isIntersect(Rectangle otherRect)
```


确定此矩形是否与其他矩形相交。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | 交叉点将用指定的矩形进行测试。 |

**退货：**
boolean - 如果此矩形与指定矩形相交则为真。否则为假。
### isPoint() {#isPoint--}
```
public boolean isPoint()
```


检查矩形是否为点，即 LLX 等于 URX，LLY 等于 URY。

**退货：**
boolean - 布尔值
### isTrivial() {#isTrivial--}
```
public boolean isTrivial()
```


检查矩形是否平凡，即大小和位置为零。

**退货：**
boolean - 布尔值
### join(Rectangle otherRect) {#join-com.aspose.pdf.Rectangle-}
```
public Rectangle join(Rectangle otherRect)
```


连接矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | 此矩形要连接到的矩形。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 描述的矩形。
### nearEquals(Rectangle other, double delta) {#nearEquals-com.aspose.pdf.Rectangle-double-}
```
public boolean nearEquals(Rectangle other, double delta)
```


检查矩形是否接近相等，即具有接近相同（最多为增量）的位置和大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.pdf/rectangle) | 将被比较的矩形。 |
| delta | double | 比较公差值。 |

**退货：**
boolean - 如果矩形相等则为 True，否则为 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String value) {#parse-java.lang.String-}
```
public static Rectangle parse(String value)
```


尝试解析字符串并从中提取矩形组件 llx、lly、urx、ury。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 要解析的字符串。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象。
### rotate(int angle) {#rotate-int-}
```
public void rotate(int angle)
```


按指定角度旋转矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| angle | int | 旋转角度。旋转枚举的成员。 |

### rotateAngle(int angle) {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```


按指定角度旋转矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| angle | int | 0 到 360 度之间的旋转角度。 |

### setLLX(double value) {#setLLX-double-}
```
public void setLLX(double value)
```


设置左下角的 X 坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setLLY(double value) {#setLLY-double-}
```
public void setLLY(double value)
```


设置 Y - 左下角的坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setURX(double value) {#setURX-double-}
```
public void setURX(double value)
```


设置 X - 右上角的坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setURY(double value) {#setURY-double-}
```
public void setURY(double value)
```


设置 Y - 右上角的坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### toArray(ITrailerable trailerable) {#toArray-com.aspose.pdf.engine.data.ITrailerable-}
```
public PdfArray toArray(ITrailerable trailerable)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |

**退货：**
[PdfArray](../../com.aspose.pdf.engine.data/pdfarray)
### toPoints() {#toPoints--}
```
public final Point[] toPoints()
```


将矩形转换为点数组（“QuadPoints”）。

**退货：**
com.aspose.pdf.点[] - 点数组。
### toRect() {#toRect--}
```
public Rectangle toRect()
```


将矩形转换为 System.Drawing.Rectangle 的实例。浮点位置和大小被截断。

**退货：**
[Rectangle](../../java.awt/rectangle) - 转换结果。
### toString() {#toString--}
```
public String toString()
```


获取矩形字符串表示形式。

**退货：**
java.lang.String - 字符串的格式为 llx,lly,urx,ury。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
