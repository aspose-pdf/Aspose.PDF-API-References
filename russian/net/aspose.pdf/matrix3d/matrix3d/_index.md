---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Конструктор Matrix3D. Конструктор создает стандартную матрицу 1 к 1 A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /ru/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Конструктор создает стандартную матрицу 1 к 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Примеры

```csharp
Matrix3D m = new Matrix3D();
```

### См. также

* класс [Matrix3D](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Конструктор принимает матрицу с следующей представлением массива: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix3DArray | Double[] | Массив данных матрицы. |

## Примеры

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### См. также

* класс [Matrix3D](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Конструктор принимает матрицу для создания копии

```csharp
public Matrix3D(Matrix3D matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix3D | Объект Matrix3D. |

### См. также

* класс [Matrix3D](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Инициализирует матрицу преобразования с заданными коэффициентами.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Double | Значение матрицы A. |
| b | Double | Значение матрицы B. |
| c | Double | Значение матрицы C. |
| d | Double | Значение матрицы D. |
| e | Double | Значение матрицы E. |
| f | Double | Значение матрицы F. |
| g | Double | Значение матрицы G. |
| h | Double | Значение матрицы H. |
| i | Double | Значение матрицы I. |
| tx | Double | Значение матрицы TX. |
| ty | Double | Значение матрицы TY. |
| tz | Double | Значение матрицы TZ. |

## Примеры

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### См. также

* класс [Matrix3D](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)