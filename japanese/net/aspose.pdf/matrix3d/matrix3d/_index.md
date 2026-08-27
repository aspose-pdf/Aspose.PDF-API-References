---
title: "Matrix3D.Matrix3D"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Matrix3D コンストラクタ。コンストラクタは標準の 1 対 1 行列 A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0 を作成します"
type: docs
weight: 10
url: /ja/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

コンストラクタは標準の 1 対 1 行列を作成します: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## 例

```csharp
Matrix3D m = new Matrix3D();
```

### 関連項目

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

コンストラクタは次の配列表現の行列を受け取ります: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| matrix3DArray | Double[] | Matrix データ配列です。 |

## 例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### 関連項目

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

コンストラクタはコピーを作成するための行列を受け取ります

```csharp
public Matrix3D(Matrix3D matrix)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D オブジェクト。 |

### 関連項目

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

指定された係数で変換行列を初期化します。

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| a | Double | A matrix の値です。 |
| b | Double | B matrix の値です。 |
| c | Double | C matrix の値です。 |
| d | Double | D matrix の値です。 |
| e | Double | E matrix の値です。 |
| f | Double | F matrix の値です。 |
| g | Double | G matrix の値。 |
| h | Double | H matrix の値。 |
| i | Double | I matrix の値。 |
| tx | Double | TX matrix の値。 |
| ty | Double | TY matrix の値。 |
| tz | Double | TZ 行列の値。 |

## 例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 関連項目

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


