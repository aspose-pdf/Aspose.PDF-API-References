---
title: "Matrix.Matrix"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор Matrix. Конструктор создает стандартную матрицу 1 к 1  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /ru/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Конструктор создаёт стандартную матрицу 1 к 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Примеры

```csharp
Matrix m = new Matrix();
```

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ]

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

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | Single[] | Массив данных матрицы. |

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Конструктор принимает матрицу для создания копии

```csharp
public Matrix(Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | Объект Matrix. |

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Инициализирует матрицу преобразования с указанными коэффициентами.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Double | Значение матрицы. |
| b | Double | Значение B матрицы. |
| c | Double | Значение C матрицы. |
| d | Double | Значение D матрицы. |
| e | Double | Значение E матрицы. |
| f | Double | Значение матрицы F. |

## Примеры

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


