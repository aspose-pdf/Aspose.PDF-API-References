---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示变换矩阵。"
type: docs
weight: 2910
url: /zh/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

类表示变换矩阵。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> 构造函数创建标准的 1 对 1 矩阵： [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> 构造函数接受具有以下数组表示的矩阵： [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> 使用指定系数初始化变换矩阵。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> 构造函数创建标准的 1 对 1 矩阵： [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> 将矩阵添加到另一个矩阵。 </p> <hr> |
| [equals](#equals-java.lang.Object-) | 将矩阵与其他对象进行比较。 |
| [getA](#getA--) | 变换矩阵的 A 成员。 |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> 将旋转转换为角度（度） </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | 变换矩阵的 B 成员。 |
| [getC](#getC--) | 变换矩阵的 C 成员。 |
| [getD](#getD--) | 变换矩阵的 D 成员。 |
| [getE](#getE--) | 变换矩阵的 E 成员。 |
| [getF](#getF--) | 变换矩阵的 F 成员。 |
| [getG](#getG--) | G 是变换矩阵的成员。 |
| [getH](#getH--) | H 是变换矩阵的成员。 |
| [getI](#getI--) | I 是变换矩阵的成员。 |
| [getTx](#getTx--) | Tx 是变换矩阵的成员。 |
| [getTy](#getTy--) | Ty 是变换矩阵的成员。 |
| [getTz](#getTz--) | Tz 是变换矩阵的成员。 |
| [hashCode](#hashCode--) | <p> 对象的哈希码。 </p> <hr> |
| [setA](#setA-double-) | 变换矩阵的 A 成员。 |
| [setB](#setB-double-) | 变换矩阵的 B 成员。 |
| [setC](#setC-double-) | 变换矩阵的 C 成员。 |
| [setD](#setD-double-) | 变换矩阵的 D 成员。 |
| [setE](#setE-double-) | 变换矩阵的 E 成员。 |
| [setF](#setF-double-) | 变换矩阵的 F 成员。 |
| [setG](#setG-double-) | G 是变换矩阵的成员。 |
| [setH](#setH-double-) | H 是变换矩阵的成员。 |
| [setI](#setI-double-) | I 是变换矩阵的成员。 |
| [setTx](#setTx-double-) | Tx 是变换矩阵的成员。 |
| [setTy](#setTy-double-) | Ty 是变换矩阵的成员。 |
| [setTz](#setTz-double-) | Tz 是变换矩阵的成员。 |
| [toString](#toString--) | 返回矩阵的文本表示。 |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> 构造函数创建标准的 1 对 1 矩阵： [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> 构造函数接受具有以下数组表示的矩阵： [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix3DArray |  | 矩阵数据数组。 |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
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
| g |  | G 矩阵的值。 |
| h |  | H 矩阵的值。 |
| i |  | I 矩阵的值。 |
| tx |  | TX 矩阵的值。 |
| ty |  | TX 矩阵的值。 |
| tz |  | TY 矩阵的值。 |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> 构造函数创建标准的 1 对 1 矩阵： [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> 将矩阵添加到另一个矩阵。 </p> <hr>

### equals {#equals-java.lang.Object-}
将矩阵与其他对象进行比较。

### getA {#getA--}
```
public double getA()
```

变换矩阵的 A 成员。

**Returns:**
double 值

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> 将旋转转换为角度（度） </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

变换矩阵的 B 成员。

**Returns:**
double 值

### getC {#getC--}
```
public double getC()
```

变换矩阵的 C 成员。

**Returns:**
double 值

### getD {#getD--}
```
public double getD()
```

变换矩阵的 D 成员。

**Returns:**
double 值

### getE {#getE--}
```
public double getE()
```

变换矩阵的 E 成员。

**Returns:**
double 值

### getF {#getF--}
```
public double getF()
```

变换矩阵的 F 成员。

**Returns:**
double 值

### getG {#getG--}
```
public double getG()
```

G 是变换矩阵的成员。

**Returns:**
double 值

### getH {#getH--}
```
public double getH()
```

H 是变换矩阵的成员。

**Returns:**
double 值

### getI {#getI--}
```
public double getI()
```

I 是变换矩阵的成员。

**Returns:**
double 值

### getTx {#getTx--}
```
public double getTx()
```

Tx 是变换矩阵的成员。

**Returns:**
double 值

### getTy {#getTy--}
```
public double getTy()
```

Ty 是变换矩阵的成员。

**Returns:**
double 值

### getTz {#getTz--}
```
public double getTz()
```

Tz 是变换矩阵的成员。

**Returns:**
double 值

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> 对象的哈希码。 </p> <hr>

**Returns:**
哈希码。

### setA {#setA-double-}
```
public void setA(double value)
```

变换矩阵的 A 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setB {#setB-double-}
```
public void setB(double value)
```

变换矩阵的 B 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setC {#setC-double-}
```
public void setC(double value)
```

变换矩阵的 C 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setD {#setD-double-}
```
public void setD(double value)
```

变换矩阵的 D 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setE {#setE-double-}
```
public void setE(double value)
```

变换矩阵的 E 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setF {#setF-double-}
```
public void setF(double value)
```

变换矩阵的 F 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setG {#setG-double-}
```
public void setG(double value)
```

G 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setH {#setH-double-}
```
public void setH(double value)
```

H 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setI {#setI-double-}
```
public void setI(double value)
```

I 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz 是变换矩阵的成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### toString {#toString--}
```
public String toString()
```

返回矩阵的文本表示。

**Returns:**
矩阵的字符串表示
