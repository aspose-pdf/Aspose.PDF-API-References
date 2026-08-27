---
title: "Matrix.Matrix"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix 构造函数。构造函数创建标准的 1 对 1 矩阵  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /zh/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

构造函数创建标准 1 对 1 矩阵: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## 示例

```csharp
Matrix m = new Matrix();
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

构造函数接受具有以下数组表示的矩阵: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | Double[] | 矩阵数据数组。 |

## 示例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

构造函数接受具有以下数组表示的矩阵: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | Single[] | 矩阵数据数组。 |

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

构造函数接受一个矩阵以创建副本

```csharp
public Matrix(Matrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | Matrix 对象。 |

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

使用指定系数初始化变换矩阵。

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | Double | A 矩阵值。 |
| b | Double | B 矩阵值。 |
| c | Double | C 矩阵值。 |
| d | Double | D 矩阵值。 |
| e | Double | E 矩阵值。 |
| f | Double | F 矩阵值。 |

## 示例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


