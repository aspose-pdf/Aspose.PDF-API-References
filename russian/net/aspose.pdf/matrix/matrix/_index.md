---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Конструктор матрицы. Конструктор создает стандартную матрицу 1 на 1 A B C D E F 1 0 0 1 0 0
type: docs
weight: 10
url: /ru/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Конструктор создает стандартную матрицу 1 на 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Примеры

```csharp
Matrix m = new Matrix();
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Конструктор принимает матрицу с следующим представлением массива: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | Double[] | Массив данных матрицы. |

## Примеры

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Конструктор принимает матрицу с следующим представлением массива: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | Single[] | Массив данных матрицы. |

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Конструктор принимает матрицу для создания копии

```csharp
public Matrix(Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | Объект матрицы. |

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Инициализирует матрицу преобразования с заданными коэффициентами.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Double | Значение матрицы A. |
| b | Double | Значение матрицы B. |
| c | Double | Значение матрицы C. |
| d | Double | Значение матрицы D. |
| e | Double | Значение матрицы E. |
| f | Double | Значение матрицы F. |

## Примеры

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)