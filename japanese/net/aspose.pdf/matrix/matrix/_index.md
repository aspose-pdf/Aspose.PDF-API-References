---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Matrix コンストラクタ。コンストラクタは標準の 1 対 1 マトリックスを作成します A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /ja/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

コンストラクタは標準の 1 対 1 マトリックスを作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## 例

```csharp
Matrix m = new Matrix();
```

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

コンストラクタは次の配列表現を持つマトリックスを受け入れます: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrixArray | Double[] | マトリックスデータ配列。 |

## 例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

コンストラクタは次の配列表現を持つマトリックスを受け入れます: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrixArray | Single[] | マトリックスデータ配列。 |

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

コンストラクタはマトリックスを受け入れてコピーを作成します

```csharp
public Matrix(Matrix matrix)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | Matrix | マトリックスオブジェクト。 |

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

指定された係数で変換マトリックスを初期化します。

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | Double | A マトリックス値。 |
| b | Double | B マトリックス値。 |
| c | Double | C マトリックス値。 |
| d | Double | D マトリックス値。 |
| e | Double | E マトリックス値。 |
| f | Double | F マトリックス値。 |

## 例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 関連項目

* クラス [Matrix](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)