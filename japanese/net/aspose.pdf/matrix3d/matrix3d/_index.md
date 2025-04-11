---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D コンストラクタ。コンストラクタは標準の 1 対 1 マトリックスを作成します A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0
type: docs
weight: 10
url: /ja/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

コンストラクタは標準の 1 対 1 マトリックスを作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## 例

```csharp
Matrix3D m = new Matrix3D();
```

### 関連項目

* クラス [Matrix3D](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

コンストラクタは次の配列表現を持つマトリックスを受け入れます: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix3DArray | Double[] | マトリックスデータ配列。 |

## 例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### 関連項目

* クラス [Matrix3D](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

コンストラクタはマトリックスを受け入れてコピーを作成します

```csharp
public Matrix3D(Matrix3D matrix)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D オブジェクト。 |

### 関連項目

* クラス [Matrix3D](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

指定された係数で変換マトリックスを初期化します。

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | Double | A マトリックス値。 |
| b | Double | B マトリックス値。 |
| c | Double | C マトリックス値。 |
| d | Double | D マトリックス値。 |
| e | Double | E マトリックス値。 |
| f | Double | F マトリックス値。 |
| g | Double | G マトリックス値。 |
| h | Double | H マトリックス値。 |
| i | Double | I マトリックス値。 |
| tx | Double | TX マトリックス値。 |
| ty | Double | TY マトリックス値。 |
| tz | Double | TZ マトリックス値。 |

## 例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 関連項目

* クラス [Matrix3D](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)