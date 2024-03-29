---
title: Matrix
second_title: Aspose.PDF for .NET API 参考
description: Constructor 创建标准 1 到 1 矩阵  ABCDEF    1 0 0 1 0 0
type: docs
weight: 10
url: /zh/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Constructor 创建标准 1 到 1 矩阵： [ ABCDEF ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

### 例子

```csharp
Matrix m = new Matrix();
```

### 也可以看看

* class [Matrix](../../matrix)
* 命名空间 [Aspose.Pdf](../../matrix)
* 部件 [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Constructor 接受具有以下数组表示的矩阵： [ ABCDEF ]

```csharp
public Matrix(double[] matrixArray)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | Double[] | 矩阵数据数组。 |

### 例子

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 也可以看看

* class [Matrix](../../matrix)
* 命名空间 [Aspose.Pdf](../../matrix)
* 部件 [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Constructor 接受具有以下数组表示的矩阵： [ ABCDEF ]

```csharp
public Matrix(float[] matrixArray)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrixArray | Single[] | 矩阵数据数组。 |

### 也可以看看

* class [Matrix](../../matrix)
* 命名空间 [Aspose.Pdf](../../matrix)
* 部件 [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Constructor 接受一个矩阵来创建一个副本

```csharp
public Matrix(Matrix matrix)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 矩阵对象。 |

### 也可以看看

* class [Matrix](../../matrix)
* 命名空间 [Aspose.Pdf](../../matrix)
* 部件 [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

用指定的系数初始化变换矩阵。

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| a | Double | 一个矩阵值。 |
| b | Double | B 矩阵值。 |
| c | Double | C 矩阵值。 |
| d | Double | D 矩阵值。 |
| e | Double | E 矩阵值。 |
| f | Double | F 矩阵值。 |

### 例子

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 也可以看看

* class [Matrix](../../matrix)
* 命名空间 [Aspose.Pdf](../../matrix)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
