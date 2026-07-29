---
title: "Matrix"
linktitle: "Matrix"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスは変換行列を表します。"
type: docs
weight: 2900
url: /ja/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

クラスは変換行列を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Matrix](#Matrix--) | <p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> 指定された係数で変換行列を初期化します。 </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | 行列を別の行列に加算します。 |
| [equals](#equals-java.lang.Object-) | 行列を他のオブジェクトと比較します。 |
| [getA](#getA--) | 変換行列の A 成分を取得します。 |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> 回転を角度（度）に変換します </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | 変換行列の B 成分を取得します。 |
| [getC](#getC--) | 変換行列の C 成分を取得します。 |
| [getD](#getD--) | 変換行列の D 成分を取得します。 |
| [getData](#getData--) | 行列のデータを配列として取得します。 |
| [getE](#getE--) | 変換行列の E 成分を取得します。 |
| [getElements](#getElements--) | 行列の要素。 |
| [getF](#getF--) | 変換行列の F 成分を取得します。 |
| [getFlipMatrix](#getFlipMatrix--) | 反転行列を取得します。 |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | 行列を PDF 配列オブジェクトに変換します。 |
| [hashCode](#hashCode--) | オブジェクトのハッシュコード。 |
| [isIdentity](#isIdentity--) | この行列が単位行列かどうかを確認します。 |
| [isInt16](#isInt16-double-) | 内部使用のみ |
| [isInt16Values](#isInt16Values--) | 内部使用のみ |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> 行列を別の行列と掛け算します。 </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> 逆行列を計算します。 </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> 指定された回転角度の行列を作成します。 </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | 指定された回転の行列を作成します。 |
| [scale](#scale-double-double-) | <p> 指定されたスケールの行列を作成します。 </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | 次の式を使用して行列で x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | 指定された行列にスケーリングを適用します。 |
| [setA](#setA-double-) | 変換行列の A 成分を設定します。 |
| [setB](#setB-double-) | 変換行列の B 成分を設定します。 |
| [setC](#setC-double-) | 変換行列の C 成分を設定します。 |
| [setD](#setD-double-) | 変換行列の D 成分を設定します。 |
| [setE](#setE-double-) | 変換行列の E 成分を設定します。 |
| [setF](#setF-double-) | 変換行列の F 成分を設定します。 |
| [skew](#skew-double-double-) | 指定された回転角度の行列を作成します。 Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | 行列のテキスト表現を返します。 |
| [transform](#transform-double-double-double:A-double:A-) | この行列を使用して座標を変換します。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | この行列を使用して点を変換します。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | 矩形を変換します。 |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | 指定された量だけ x および y 方向に行列を平行移動します。 |
| [unScale](#unScale-double-double-double:A-double:A-) | 次の式を使用して x1 と y1 を元に戻し、行列変換前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | 次の式を使用して x1 と y1 を元に戻し、行列変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrixArray |  | 行列データ配列。 |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrixArray |  | 行列データ配列。 |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> コンストラクタは標準的な 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
行列を別の行列に加算します。

### equals {#equals-java.lang.Object-}
行列を他のオブジェクトと比較します。

### getA {#getA--}
```
public double getA()
```

変換行列の A 成分を取得します。

**Returns:**
double 値

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> 回転を角度（度）に変換します </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

変換行列の B 成分を取得します。

**Returns:**
double 値

### getC {#getC--}
```
public double getC()
```

変換行列の C 成分を取得します。

**Returns:**
double 値

### getD {#getD--}
```
public double getD()
```

変換行列の D 成分を取得します。

**Returns:**
double 値

### getData {#getData--}
```
public final double[] getData()
```

行列のデータを配列として取得します。

**Returns:**
double 値の配列

### getE {#getE--}
```
public double getE()
```

変換行列の E 成分を取得します。

**Returns:**
double 値

### getElements {#getElements--}
```
public float[] getElements()
```

行列の要素。

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

変換行列の F 成分を取得します。

**Returns:**
double 値

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

反転行列を取得します。

**Returns:**
行列インスタンス

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
行列を PDF 配列オブジェクトに変換します。

### hashCode {#hashCode--}
```
public int hashCode()
```

オブジェクトのハッシュコード。

**Returns:**
ハッシュコード。

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

この行列が単位行列かどうかを確認します。

**Returns:**
ブール値

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

内部使用のみ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

**Returns:**
ブール値

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

内部使用のみ

**Returns:**
ブール値

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> 行列を別の行列と掛け算します。 </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> 逆行列を計算します。 </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
逆行列。

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> 指定された回転角度の行列を作成します。 </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha |  | ラジアン単位の回転角。 |

**Returns:**
変換行列。

### rotation {#rotation-com.aspose.pdf.Rotation-}
指定された回転の行列を作成します。

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> 指定されたスケールの行列を作成します。 </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | X スケール。 |
| y |  | Y スケール。 |

**Returns:**
変換行列。

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

次の式を使用して行列で x と y をスケーリングします: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | 入力 X 座標 |
| y |  | 入力 Y 座標 |
| x1 |  | 出力 X 座標 |
| y1 |  | 出力 Y 座標 |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
指定された行列にスケーリングを適用します。

### setA {#setA-double-}
```
public void setA(double value)
```

変換行列の A 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setB {#setB-double-}
```
public void setB(double value)
```

変換行列の B 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setC {#setC-double-}
```
public void setC(double value)
```

変換行列の C 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setD {#setD-double-}
```
public void setD(double value)
```

変換行列の D 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setE {#setE-double-}
```
public void setE(double value)
```

変換行列の E 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setF {#setF-double-}
```
public void setF(double value)
```

変換行列の F 成分を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

指定された回転角度の行列を作成します。 Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha |  | ラジアン単位の X せん断角。 |
| beta |  | ラジアン単位の Y せん断角。 |

**Returns:**
変換行列。

### toString {#toString--}
```
public String toString()
```

行列のテキスト表現を返します。

**Returns:**
行列の文字列表現

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

この行列を使用して座標を変換します。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x |  | X 座標。 |
| y |  | Y 座標。 |
| x1 |  | 変換後 X 座標。 |
| y1 |  | 変換後 Y 座標。 |

### transform {#transform-com.aspose.pdf.Point-}
この行列を使用して点を変換します。 Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
矩形を変換します。

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
指定された量だけ x および y 方向に行列を平行移動します。

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

次の式を使用して x1 と y1 を元に戻し、行列変換前の x と y を返します: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B);

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 |  | 入力 X 座標 |
| y1 |  | 入力 Y 座標 |
| x |  | 出力 X 座標 |
| y |  | 出力 Y 座標 |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

次の式を使用して x1 と y1 を元に戻し、行列変換前の x と y を返します: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x1 |  | 入力 X 座標 |
| y1 |  | 入力 Y 座標 |
| x |  | 出力 X 座標 |
| y |  | 出力 Y 座標 |
