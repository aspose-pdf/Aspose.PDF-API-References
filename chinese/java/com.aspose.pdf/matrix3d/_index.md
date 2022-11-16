---
title: Matrix3D
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示变换矩阵。
type: docs
weight: 210
url: /zh/java/com.aspose.pdf/matrix3d/
---
**遗产：**
java.lang.Object
```
public final class Matrix3D
```

类表示变换矩阵。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix3D()](#Matrix3D--) | 构造函数创建标准的 1 对 1 矩阵：[ ABCDEFGHI Tx Ty Tz] =[ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D(double[] matrix3DArray)](#Matrix3D-double---) | 构造函数接受具有以下数组表示的矩阵：[ ABCDEFGHI Tx Ty Tz] |
| [Matrix3D(Matrix3D matrix)](#Matrix3D-com.aspose.pdf.Matrix3D-) | 构造函数接受一个矩阵来创建一个副本 |
| [Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | 使用此矩阵转换点。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Matrix3D other)](#add-com.aspose.pdf.Matrix3D-) | 将矩阵乘以其他矩阵。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 将矩阵与其他对象进行比较。 |
| [getA()](#getA--) | 变换矩阵的成员。 |
| [getAngle(int rotation)](#getAngle-int-) | 为给定的旋转角度创建矩阵。 |
| [getB()](#getB--) | 变换矩阵的 B 成员。 |
| [getC()](#getC--) | 变换矩阵的 C 成员。 |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | D 变换矩阵的成员。 |
| [getE()](#getE--) | 变换矩阵的 E 成员。 |
| [getF()](#getF--) | 变换矩阵的 F 成员。 |
| [getG()](#getG--) | 变换矩阵的 G 成员。 |
| [getH()](#getH--) | 变换矩阵的H成员。 |
| [getI()](#getI--) | 我是变换矩阵的成员。 |
| [getTx()](#getTx--) | Tx 变换矩阵的成员。 |
| [getTy()](#getTy--) | 变换矩阵的 Ty 成员。 |
| [getTz()](#getTz--) | 变换矩阵的 Tz 成员。 |
| [hashCode()](#hashCode--) | 计算反向矩阵。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(double value)](#setA-double-) | 变换矩阵的成员。 |
| [setB(double value)](#setB-double-) | 变换矩阵的 B 成员。 |
| [setC(double value)](#setC-double-) | 变换矩阵的 C 成员。 |
| [setD(double value)](#setD-double-) | D 变换矩阵的成员。 |
| [setE(double value)](#setE-double-) | 变换矩阵的 E 成员。 |
| [setF(double value)](#setF-double-) | 变换矩阵的 F 成员。 |
| [setG(double value)](#setG-double-) | 变换矩阵的 G 成员。 |
| [setH(double value)](#setH-double-) | 变换矩阵的H成员。 |
| [setI(double value)](#setI-double-) | 我是变换矩阵的成员。 |
| [setTx(double value)](#setTx-double-) | Tx 变换矩阵的成员。 |
| [setTy(double value)](#setTy-double-) | 变换矩阵的 Ty 成员。 |
| [setTz(double value)](#setTz-double-) | 变换矩阵的 Tz 成员。 |
| [toString()](#toString--) | 返回矩阵的文本表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix3D() {#Matrix3D--}
```
public Matrix3D()
```


构造函数创建标准的 1 对 1 矩阵：[ ABCDEFGHI Tx Ty Tz] =[ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

--------------------

```
Matrix3D m = new Matrix3D();
```

### Matrix3D(double[] matrix3DArray) {#Matrix3D-double---}
```
public Matrix3D(double[] matrix3DArray)
```


构造函数接受具有以下数组表示的矩阵：[ ABCDEFGHI Tx Ty Tz]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
 Matrix3D m = new Matrix3D(c);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix3DArray | double[] | 矩阵数据数组。 |

### Matrix3D(Matrix3D matrix) {#Matrix3D-com.aspose.pdf.Matrix3D-}
```
public Matrix3D(Matrix3D matrix)
```


构造函数接受一个矩阵来创建一个副本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix3D](../../com.aspose.pdf/matrix3d) | Matrix3D 对象。 |

### Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz) {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


使用此矩阵转换点。

变换矩形。如果角度不是 90\* N 度然后返回边界矩形。

用指定的系数初始化变换矩阵。

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Point p = new Point(5, 5);
  Point p1 = m.transform(p);
```

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Rectangle r = new Rectangle(0, 0, 100, 100);
  Rectangle r1 = m.transform(r1);
```

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
| g | double | G 矩阵值。 |
| h | double | H 矩阵值。 |
| i | double | 我矩阵值。 |
| tx | double | TX 矩阵值。 |
| ty | double | TX 矩阵值。 |
| tz | double | TY 矩阵值。 |

### add(Matrix3D other) {#add-com.aspose.pdf.Matrix3D-}
```
public Matrix3D add(Matrix3D other)
```


将矩阵乘以其他矩阵。

将矩阵添加到其他矩阵。

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
  Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
  Matrix c= a.Multiply(b);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | [Matrix3D](../../com.aspose.pdf/matrix3d) | 要添加的矩阵。 |

**退货：**
[Matrix3D](../../com.aspose.pdf/matrix3d) - 矩阵相加的结果。
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
布尔值 - 如果其他对象是 Matrix3D 且所有矩阵成员都等于矩阵的相应成员，则返回 true
### getA() {#getA--}
```
public double getA()
```


变换矩阵的成员。

**退货：**
双倍价值
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


为给定的旋转角度创建矩阵。

为给定的旋转角度创建矩阵。

为给定比例创建矩阵。

将旋转转换为角度（度）

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.scale(x, y);
```

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


变换矩阵的 B 成员。

**退货：**
双倍价值
### getC() {#getC--}
```
public double getC()
```


变换矩阵的 C 成员。

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


D 变换矩阵的成员。

**退货：**
双倍价值
### getE() {#getE--}
```
public double getE()
```


变换矩阵的 E 成员。

**退货：**
双倍价值
### getF() {#getF--}
```
public double getF()
```


变换矩阵的 F 成员。

**退货：**
双倍价值
### getG() {#getG--}
```
public double getG()
```


变换矩阵的 G 成员。

**退货：**
双倍价值
### getH() {#getH--}
```
public double getH()
```


变换矩阵的H成员。

**退货：**
双倍价值
### getI() {#getI--}
```
public double getI()
```


我是变换矩阵的成员。

**退货：**
双倍价值
### getTx() {#getTx--}
```
public double getTx()
```


Tx 变换矩阵的成员。

**退货：**
双倍价值
### getTy() {#getTy--}
```
public double getTy()
```


变换矩阵的 Ty 成员。

**退货：**
双倍价值
### getTz() {#getTz--}
```
public double getTz()
```


变换矩阵的 Tz 成员。

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public int hashCode()
```


计算反向矩阵。

对象的哈希码。

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
  Matrix m1 = m.reverse();
```

**退货：**
int - 哈希码。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setA(double value) {#setA-double-}
```
public void setA(double value)
```


变换矩阵的成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setB(double value) {#setB-double-}
```
public void setB(double value)
```


变换矩阵的 B 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setC(double value) {#setC-double-}
```
public void setC(double value)
```


变换矩阵的 C 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setD(double value) {#setD-double-}
```
public void setD(double value)
```


D 变换矩阵的成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setE(double value) {#setE-double-}
```
public void setE(double value)
```


变换矩阵的 E 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setF(double value) {#setF-double-}
```
public void setF(double value)
```


变换矩阵的 F 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setG(double value) {#setG-double-}
```
public void setG(double value)
```


变换矩阵的 G 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setH(double value) {#setH-double-}
```
public void setH(double value)
```


变换矩阵的H成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setI(double value) {#setI-double-}
```
public void setI(double value)
```


我是变换矩阵的成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setTx(double value) {#setTx-double-}
```
public void setTx(double value)
```


Tx 变换矩阵的成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setTy(double value) {#setTy-double-}
```
public void setTy(double value)
```


变换矩阵的 Ty 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setTz(double value) {#setTz-double-}
```
public void setTz(double value)
```


变换矩阵的 Tz 成员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### toString() {#toString--}
```
public String toString()
```


返回矩阵的文本表示。

**退货：**
java.lang.String - 矩阵的字符串表示
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
