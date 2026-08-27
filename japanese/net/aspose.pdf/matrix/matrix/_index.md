---
title: "Matrix.Matrix"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix コンストラクタ。コンストラクタは標準の 1 対 1 行列を作成します  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /ja/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## 例

```csharp
Matrix m = new Matrix();
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| matrixArray | Double[] | Matrix データ配列です。 |

## 例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| matrixArray | Single[] | Matrix データ配列です。 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

コンストラクタはコピーを作成するための行列を受け取ります

```csharp
public Matrix(Matrix matrix)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| matrix | Matrix | Matrix オブジェクトです。 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

指定された係数で変換行列を初期化します。

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| a | Double | A matrix の値です。 |
| b | Double | B matrix の値です。 |
| c | Double | C matrix の値です。 |
| d | Double | D matrix の値です。 |
| e | Double | E matrix の値です。 |
| f | Double | F matrix の値です。 |

## 例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


