---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスは変換行列を表します。"
type: docs
weight: 2910
url: /ja/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

クラスは変換行列を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> 指定された係数で変換行列を初期化します。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> 行列を別の行列に加算します。 </p> <hr> |
| [equals](#equals-java.lang.Object-) | 行列を他のオブジェクトと比較します。 |
| [getA](#getA--) | 変換行列のメンバー A。 |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> 回転を角度（度）に変換します </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | 変換行列のメンバー B。 |
| [getC](#getC--) | 変換行列のメンバー C。 |
| [getD](#getD--) | 変換行列のメンバー D。 |
| [getE](#getE--) | 変換行列のメンバー E。 |
| [getF](#getF--) | 変換行列のメンバー F。 |
| [getG](#getG--) | 変換行列の G メンバー。 |
| [getH](#getH--) | 変換行列の H メンバー。 |
| [getI](#getI--) | 変換行列の I メンバー。 |
| [getTx](#getTx--) | 変換行列の Tx メンバー。 |
| [getTy](#getTy--) | 変換行列の Ty メンバー。 |
| [getTz](#getTz--) | 変換行列の Tz メンバー。 |
| [hashCode](#hashCode--) | <p> オブジェクトのハッシュコード。 </p> <hr> |
| [setA](#setA-double-) | 変換行列のメンバー A。 |
| [setB](#setB-double-) | 変換行列のメンバー B。 |
| [setC](#setC-double-) | 変換行列のメンバー C。 |
| [setD](#setD-double-) | 変換行列のメンバー D。 |
| [setE](#setE-double-) | 変換行列のメンバー E。 |
| [setF](#setF-double-) | 変換行列のメンバー F。 |
| [setG](#setG-double-) | 変換行列の G メンバー。 |
| [setH](#setH-double-) | 変換行列の H メンバー。 |
| [setI](#setI-double-) | 変換行列の I メンバー。 |
| [setTx](#setTx-double-) | 変換行列の Tx メンバー。 |
| [setTy](#setTy-double-) | 変換行列の Ty メンバー。 |
| [setTz](#setTz-double-) | 変換行列の Tz メンバー。 |
| [toString](#toString--) | 行列のテキスト表現を返します。 |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix3DArray |  | 行列データ配列。 |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> 指定された係数で変換行列を初期化します。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a |  | A 行列の値。 |
| b |  | B 行列の値。 |
| c |  | C 行列の値。 |
| d |  | D 行列の値。 |
| e |  | E 行列の値。 |
| f |  | F 行列の値。 |
| g |  | G 行列の値。 |
| h |  | H 行列の値。 |
| i |  | I 行列の値。 |
| tx |  | TX 行列の値。 |
| ty |  | TX 行列の値。 |
| tz |  | TY 行列の値。 |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> 行列を別の行列に加算します。 </p> <hr>

### equals {#equals-java.lang.Object-}
行列を他のオブジェクトと比較します。

### getA {#getA--}
```
public double getA()
```

変換行列のメンバー A。

**Returns:**
double 値

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> 回転を角度（度）に変換します </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

変換行列のメンバー B。

**Returns:**
double 値

### getC {#getC--}
```
public double getC()
```

変換行列のメンバー C。

**Returns:**
double 値

### getD {#getD--}
```
public double getD()
```

変換行列のメンバー D。

**Returns:**
double 値

### getE {#getE--}
```
public double getE()
```

変換行列のメンバー E。

**Returns:**
double 値

### getF {#getF--}
```
public double getF()
```

変換行列のメンバー F。

**Returns:**
double 値

### getG {#getG--}
```
public double getG()
```

変換行列の G メンバー。

**Returns:**
double 値

### getH {#getH--}
```
public double getH()
```

変換行列の H メンバー。

**Returns:**
double 値

### getI {#getI--}
```
public double getI()
```

変換行列の I メンバー。

**Returns:**
double 値

### getTx {#getTx--}
```
public double getTx()
```

変換行列の Tx メンバー。

**Returns:**
double 値

### getTy {#getTy--}
```
public double getTy()
```

変換行列の Ty メンバー。

**Returns:**
double 値

### getTz {#getTz--}
```
public double getTz()
```

変換行列の Tz メンバー。

**Returns:**
double 値

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> オブジェクトのハッシュコード。 </p> <hr>

**Returns:**
ハッシュコード。

### setA {#setA-double-}
```
public void setA(double value)
```

変換行列のメンバー A。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setB {#setB-double-}
```
public void setB(double value)
```

変換行列のメンバー B。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setC {#setC-double-}
```
public void setC(double value)
```

変換行列のメンバー C。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setD {#setD-double-}
```
public void setD(double value)
```

変換行列のメンバー D。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setE {#setE-double-}
```
public void setE(double value)
```

変換行列のメンバー E。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setF {#setF-double-}
```
public void setF(double value)
```

変換行列のメンバー F。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setG {#setG-double-}
```
public void setG(double value)
```

変換行列の G メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setH {#setH-double-}
```
public void setH(double value)
```

変換行列の H メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setI {#setI-double-}
```
public void setI(double value)
```

変換行列の I メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

変換行列の Tx メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

変換行列の Ty メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

変換行列の Tz メンバー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### toString {#toString--}
```
public String toString()
```

行列のテキスト表現を返します。

**Returns:**
行列の文字列表現
