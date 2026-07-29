---
title: "Matrix3D.Matrix3D"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix3D 构造函数。构造函数创建标准 1 到 1 matrix  A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0"
type: docs
weight: 10
url: /zh/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

构造函数创建标准的 1 对 1 矩阵: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## 示例

```csharp
Matrix3D m = new Matrix3D();
```

### 另请参见

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

构造函数接受具有以下数组表示形式的矩阵: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix3DArray | Double[] | 矩阵数据数组。 |

## 示例

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### 另请参见

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

构造函数接受一个矩阵以创建副本

```csharp
public Matrix3D(Matrix3D matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D 对象。 |

### 另请参见

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

使用指定系数初始化变换矩阵。

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | Double | A 矩阵值。 |
| b | Double | B 矩阵值。 |
| c | Double | C 矩阵值。 |
| d | Double | D 矩阵值。 |
| e | Double | E 矩阵值。 |
| f | Double | F 矩阵值。 |
| g | Double | G matrix 值。 |
| h | Double | H matrix 值。 |
| i | Double | I matrix 值。 |
| tx | Double | TX matrix 值。 |
| ty | Double | TY matrix 值。 |
| tz | Double | TZ 矩阵值。 |

## 示例

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 另请参见

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


