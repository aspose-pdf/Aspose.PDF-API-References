---
title: "Matrix"
linktitle: "Matrix"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示变换矩阵。"
type: docs
weight: 2900
url: /zh/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

类表示变换矩阵。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix](#Matrix--) | <p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> 构造函数接受具有以下数组表示形式的矩阵: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> 使用指定系数初始化变换矩阵。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> 构造函数接受具有以下数组表示形式的矩阵: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | 将矩阵添加到另一个矩阵。 |
| [equals](#equals-java.lang.Object-) | 将矩阵与其他对象进行比较。 |
| [getA](#getA--) | 获取变换矩阵的 A 成员。 |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> 将旋转转换为角度（度） </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | 获取变换矩阵的 B 成员。 |
| [getC](#getC--) | 获取变换矩阵的 C 成员。 |
| [getD](#getD--) | 获取变换矩阵的 D 成员。 |
| [getData](#getData--) | 获取 Matrix 的数据为数组。 |
| [getE](#getE--) | 获取变换矩阵的 E 成员。 |
| [getElements](#getElements--) | 矩阵的元素。 |
| [getF](#getF--) | 获取变换矩阵的 F 成员。 |
| [getFlipMatrix](#getFlipMatrix--) | 获取翻转矩阵。 |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | 将矩阵转换为 PDF 数组对象。 |
| [hashCode](#hashCode--) | 对象的哈希码。 |
| [isIdentity](#isIdentity--) | 检查此矩阵是否为单位矩阵。 |
| [isInt16](#isInt16-double-) | 仅供内部使用 |
| [isInt16Values](#isInt16Values--) | 仅供内部使用 |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> 将矩阵与另一个矩阵相乘。 </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> 计算逆矩阵。 </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> 为给定的旋转角度创建矩阵。 </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | 为给定的旋转创建矩阵。 |
| [scale](#scale-double-double-) | <p> 为给定的缩放创建矩阵。 </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | 使用以下公式通过矩阵缩放 x 和 y：x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | 对给定的矩阵应用缩放。 |
| [setA](#setA-double-) | 设置变换矩阵的 A 成员。 |
| [setB](#setB-double-) | 设置变换矩阵的 B 成员。 |
| [setC](#setC-double-) | 设置变换矩阵的 C 成员。 |
| [setD](#setD-double-) | 设置变换矩阵的 D 成员。 |
| [setE](#setE-double-) | 设置变换矩阵的 E 成员。 |
| [setF](#setF-double-) | 设置变换矩阵的 F 成员。 |
| [skew](#skew-double-double-) | 为给定的旋转角度创建矩阵。 Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | 返回矩阵的文本表示。 |
| [transform](#transform-double-double-double:A-double:A-) | 使用此矩阵转换坐标。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | 使用此矩阵转换点。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | 转换矩形。 |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | 在 x 和 y 方向上按指定量平移矩阵。 |
| [unScale](#unScale-double-double-double:A-double:A-) | 使用以下公式将 x1 和 y1 缩放回并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | 使用以下公式将 x1 和 y1 反向变换并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。 |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> 构造函数接受具有以下数组表示形式的矩阵: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray |  | 矩阵数据数组。 |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

<p> 使用指定系数初始化变换矩阵。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a |  | A 矩阵值。 |
| b |  | B 矩阵值。 |
| c |  | C 矩阵值。 |
| d |  | D 矩阵值。 |
| e |  | E 矩阵值。 |
| f |  | F 矩阵值。 |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> 构造函数接受具有以下数组表示形式的矩阵: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray |  | 矩阵数据数组。 |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> 构造函数创建标准的 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
将矩阵添加到另一个矩阵。

### equals {#equals-java.lang.Object-}
将矩阵与其他对象进行比较。

### getA {#getA--}
```
public double getA()
```

获取变换矩阵的 A 成员。

**Returns:**
double 值

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> 将旋转转换为角度（度） </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

获取变换矩阵的 B 成员。

**Returns:**
double 值

### getC {#getC--}
```
public double getC()
```

获取变换矩阵的 C 成员。

**Returns:**
double 值

### getD {#getD--}
```
public double getD()
```

获取变换矩阵的 D 成员。

**Returns:**
double 值

### getData {#getData--}
```
public final double[] getData()
```

获取 Matrix 的数据为数组。

**Returns:**
double 值数组

### getE {#getE--}
```
public double getE()
```

获取变换矩阵的 E 成员。

**Returns:**
double 值

### getElements {#getElements--}
```
public float[] getElements()
```

矩阵的元素。

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

获取变换矩阵的 F 成员。

**Returns:**
double 值

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

获取翻转矩阵。

**Returns:**
矩阵实例

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
将矩阵转换为 PDF 数组对象。

### hashCode {#hashCode--}
```
public int hashCode()
```

对象的哈希码。

**Returns:**
哈希码。

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

检查此矩阵是否为单位矩阵。

**Returns:**
布尔值

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

仅供内部使用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

**Returns:**
布尔值

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

仅供内部使用

**Returns:**
布尔值

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> 将矩阵与另一个矩阵相乘。 </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> 计算逆矩阵。 </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
反转矩阵。

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> 为给定的旋转角度创建矩阵。 </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha |  | 以弧度表示的旋转角度。 |

**Returns:**
变换矩阵。

### rotation {#rotation-com.aspose.pdf.Rotation-}
为给定的旋转创建矩阵。

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> 为给定的缩放创建矩阵。 </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | X 方向缩放。 |
| y |  | Y 方向缩放。 |

**Returns:**
变换矩阵。

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

使用以下公式通过矩阵缩放 x 和 y：x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | 输入 X 坐标 |
| y |  | 输入 Y 坐标 |
| x1 |  | 输出 X 坐标 |
| y1 |  | 输出 Y 坐标 |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
对给定的矩阵应用缩放。

### setA {#setA-double-}
```
public void setA(double value)
```

设置变换矩阵的 A 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setB {#setB-double-}
```
public void setB(double value)
```

设置变换矩阵的 B 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setC {#setC-double-}
```
public void setC(double value)
```

设置变换矩阵的 C 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setD {#setD-double-}
```
public void setD(double value)
```

设置变换矩阵的 D 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setE {#setE-double-}
```
public void setE(double value)
```

设置变换矩阵的 E 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setF {#setF-double-}
```
public void setF(double value)
```

设置变换矩阵的 F 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

为给定的旋转角度创建矩阵。 Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha |  | X 方向倾斜角（弧度）。 |
| beta |  | Y 方向倾斜角（弧度）。 |

**Returns:**
变换矩阵。

### toString {#toString--}
```
public String toString()
```

返回矩阵的文本表示。

**Returns:**
矩阵的字符串表示

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

使用此矩阵转换坐标。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x |  | X 坐标。 |
| y |  | Y 坐标。 |
| x1 |  | 变换后的 X 坐标。 |
| y1 |  | 变换后的 Y 坐标。 |

### transform {#transform-com.aspose.pdf.Point-}
使用此矩阵转换点。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
转换矩形。

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
在 x 和 y 方向上按指定量平移矩阵。

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

使用以下公式将 x1 和 y1 缩放回并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 |  | 输入 X 坐标 |
| y1 |  | 输入 Y 坐标 |
| x |  | 输出 X 坐标 |
| y |  | 输出 Y 坐标 |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

使用以下公式将 x1 和 y1 反向变换并返回矩阵变换前的 x 和 y：x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 |  | 输入 X 坐标 |
| y1 |  | 输入 Y 坐标 |
| x |  | 输出 X 坐标 |
| y |  | 输出 Y 坐标 |
