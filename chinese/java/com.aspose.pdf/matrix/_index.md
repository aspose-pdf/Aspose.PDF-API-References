---
title: Matrix
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示变换矩阵。
type: docs
weight: 209
url: /zh/java/com.aspose.pdf/matrix/
---
**遗产：**
java.lang.Object
```
public final class Matrix
```

类表示变换矩阵。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix()](#Matrix--) | 构造函数创建标准的 1 对 1 矩阵：[ ABCDEF ] =[ 1, 0, 0, 1, 0, 0] |
| [Matrix(double[] matrixArray)](#Matrix-double---) | 构造函数接受具有以下数组表示的矩阵：[ ABCDEF ] |
| [Matrix(float[] matrixArray)](#Matrix-float---) | 构造函数接受具有以下数组表示的矩阵：[ ABCDEF ] |
| [Matrix(Matrix matrix)](#Matrix-com.aspose.pdf.Matrix-) | 构造函数接受一个矩阵来创建一个副本 |
| [Matrix(double a, double b, double c, double d, double e, double f)](#Matrix-double-double-double-double-double-double-) | 用指定的系数初始化变换矩阵。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Matrix other)](#add-com.aspose.pdf.Matrix-) | 将矩阵添加到其他矩阵。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 将矩阵与其他对象进行比较。 |
| [getA()](#getA--) | 获取变换矩阵的成员。 |
| [getAngle(int rotation)](#getAngle-int-) | Transaltes 旋转成角度（度） |
| [getB()](#getB--) | 获取变换矩阵的 B 成员。 |
| [getC()](#getC--) | 获取变换矩阵的 C 成员。 |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 获取变换矩阵的 D 成员。 |
| [getData()](#getData--) | 获取 Matrix 的数据作为数组。 |
| [getE()](#getE--) | 获取变换矩阵的 E 成员。 |
| [getElements()](#getElements--) | 矩阵的元素。 |
| [getF()](#getF--) | 获取变换矩阵的 F 成员。 |
| [getMatrix(ITrailerable trailer)](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | 将矩阵转换为 PDF 数组对象。 |
| [hashCode()](#hashCode--) | 对象的哈希码。 |
| [isInt16(double value)](#isInt16-double-) | 仅供内部使用 |
| [isInt16Values()](#isInt16Values--) | 仅供内部使用 |
| [multiply(Matrix other)](#multiply-com.aspose.pdf.Matrix-) | 将矩阵乘以其他矩阵。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | 计算反向矩阵。 |
| [rotation(double alpha)](#rotation-double-) | 为给定的旋转角度创建矩阵。 |
| [rotation(int rotation)](#rotation-int-) | 为给定的旋转创建矩阵。 |
| [scale(double x, double y)](#scale-double-double-) | 为给定比例创建矩阵。 |
| [setA(double value)](#setA-double-) | Set 变换矩阵的一个成员。 |
| [setB(double value)](#setB-double-) | 设置变换矩阵的 B 成员。 |
| [setC(double value)](#setC-double-) | 设置变换矩阵的 C 成员。 |
| [setD(double value)](#setD-double-) | 设置变换矩阵的 D 成员。 |
| [setE(double value)](#setE-double-) | 设置变换矩阵的 E 成员。 |
| [setF(double value)](#setF-double-) | 设置变换矩阵的 F 成员。 |
| [skew(double alpha, double beta)](#skew-double-double-) | 为给定的旋转角度创建矩阵。 |
| [toString()](#toString--) | 返回矩阵的文本表示。 |
| [transform(Point p)](#transform-com.aspose.pdf.Point-) | 使用此矩阵转换点。 |
| [transform(Rectangle rect)](#transform-com.aspose.pdf.Rectangle-) | 变换矩形。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


构造函数创建标准的 1 对 1 矩阵：[ ABCDEF ] =[ 1, 0, 0, 1, 0, 0]

--------------------

```
Matrix m = new Matrix();
```

### Matrix(double[] matrixArray) {#Matrix-double---}
```
public Matrix(double[] matrixArray)
```


构造函数接受具有以下数组表示的矩阵：[ ABCDEF ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | double[] | 矩阵数据数组。 |

### Matrix(float[] matrixArray) {#Matrix-float---}
```
public Matrix(float[] matrixArray)
```


构造函数接受具有以下数组表示的矩阵：[ ABCDEF ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | float[] | 矩阵数据数组。 |

### Matrix(Matrix matrix) {#Matrix-com.aspose.pdf.Matrix-}
```
public Matrix(Matrix matrix)
```


构造函数接受一个矩阵来创建一个副本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.pdf/matrix) | 矩阵对象。 |

### Matrix(double a, double b, double c, double d, double e, double f) {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```


用指定的系数初始化变换矩阵。

--------------------

```
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| a | double | 矩阵值。 |
| b | double | 矩阵值。 |
| c | double | C 矩阵值。 |
| d | double | D 矩阵值。 |
| e | double | E 矩阵值。 |
| f | double | F 矩阵值。 |

### add(Matrix other) {#add-com.aspose.pdf.Matrix-}
```
public Matrix add(Matrix other)
```


将矩阵添加到其他矩阵。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | 要添加的矩阵。 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 矩阵相加的结果。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


将矩阵与其他对象进行比较。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的对象。 |

**退货：**
boolean - 如果其他对象是 Matrix 且所有矩阵成员都等于矩阵的对应成员，则返回 true
### getA() {#getA--}
```
public double getA()
```


获取变换矩阵的成员。

**退货：**
双倍价值
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Transaltes 旋转成角度（度）

--------------------

```
double angle = Matrix.getAngle(Rotation.on90);
 Matrix m = Matrix.rotation(angle);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotation | int | 旋转值。 |

**退货：**
双 - 角度值。
### getB() {#getB--}
```
public double getB()
```


获取变换矩阵的 B 成员。

**退货：**
双倍价值
### getC() {#getC--}
```
public double getC()
```


获取变换矩阵的 C 成员。

**退货：**
双倍价值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getD() {#getD--}
```
public double getD()
```


获取变换矩阵的 D 成员。

**退货：**
双倍价值
### getData() {#getData--}
```
public final double[] getData()
```


获取 Matrix 的数据作为数组。

**退货：**
双倍的[- 双精度值数组
### getE() {#getE--}
```
public double getE()
```


获取变换矩阵的 E 成员。

**退货：**
双倍价值
### getElements() {#getElements--}
```
public float[] getElements()
```


矩阵的元素。

**退货：**
漂浮[- 漂浮[大批
### getF() {#getF--}
```
public double getF()
```


获取变换矩阵的 F 成员。

**退货：**
双倍价值
### getMatrix(ITrailerable trailer) {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
```
public IPdfArray getMatrix(ITrailerable trailer)
```


将矩阵转换为 PDF 数组对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| trailer | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | 拖车物体 |

**退货：**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) 转换结果
### hashCode() {#hashCode--}
```
public int hashCode()
```


对象的哈希码。

**退货：**
int - 哈希码。
### isInt16(double value) {#isInt16-double-}
```
public static boolean isInt16(double value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

**退货：**
boolean - 布尔值
### isInt16Values() {#isInt16Values--}
```
public boolean isInt16Values()
```


仅供内部使用

**退货：**
boolean - 布尔值
### multiply(Matrix other) {#multiply-com.aspose.pdf.Matrix-}
```
public Matrix multiply(Matrix other)
```


将矩阵乘以其他矩阵。

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
 Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
 Matrix c= a.multiply(b);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | 乘数矩阵。 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 乘法的结果。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reverse() {#reverse--}
```
public Matrix reverse()
```


计算反向矩阵。

--------------------

```
Matrix m = Matrix.rotation(Math.PI / 2);
 Matrix m1 = m.reverse();
```

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 反向矩阵。
### rotation(double alpha) {#rotation-double-}
```
public static Matrix rotation(double alpha)
```


为给定的旋转角度创建矩阵。

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| alpha | double | 以弧度为单位的旋转角度。 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 变换矩阵。
### rotation(int rotation) {#rotation-int-}
```
public static Matrix rotation(int rotation)
```


为给定的旋转创建矩阵。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotation | int | 回转。有效值为：无、on90、on180、on270 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 带旋转的矩阵实例。
### scale(double x, double y) {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```


为给定比例创建矩阵。

--------------------

```
Matrix m = Matrix.scale(x, y);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 缩放 x。 |
| y | double | 缩放 y。 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 变换矩阵。
### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Set 变换矩阵的一个成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setB(double value) {#setB-double-}
```
public void setB(double value)
```


设置变换矩阵的 B 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setC(double value) {#setC-double-}
```
public void setC(double value)
```


设置变换矩阵的 C 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setD(double value) {#setD-double-}
```
public void setD(double value)
```


设置变换矩阵的 D 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setE(double value) {#setE-double-}
```
public void setE(double value)
```


设置变换矩阵的 E 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setF(double value) {#setF-double-}
```
public void setF(double value)
```


设置变换矩阵的 F 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### skew(double alpha, double beta) {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```


为给定的旋转角度创建矩阵。

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| alpha | double | 以弧度为单位的倾斜 x 角度。 |
| beta | double | 以弧度为单位的倾斜 y 角。 |

**退货：**
[Matrix](../../com.aspose.pdf/matrix) - 变换矩阵。
### toString() {#toString--}
```
public String toString()
```


返回矩阵的文本表示。

**退货：**
java.lang.String - 矩阵的字符串表示
### transform(Point p) {#transform-com.aspose.pdf.Point-}
```
public Point transform(Point p)
```


使用此矩阵转换点。

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Point p = new Point(5, 5);
 Point p1 = m.transform(p);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| p | [Point](../../com.aspose.pdf/point) | 将被转换的点。 |

**退货：**
[Point](../../com.aspose.pdf/point) - 转换结果。
### transform(Rectangle rect) {#transform-com.aspose.pdf.Rectangle-}
```
public Rectangle transform(Rectangle rect)
```


变换矩形。如果角度不是 90\* N 度然后返回边界矩形。

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Rectangle r = new Rectangle(0, 0, 100, 100);
 Rectangle r1 = m.transform(r1);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 要变换的矩形。 |

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 变形后的矩形。
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
