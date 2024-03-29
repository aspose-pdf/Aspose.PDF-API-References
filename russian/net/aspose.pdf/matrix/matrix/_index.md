---
title: Matrix
second_title: Aspose.PDF для справочника API .NET
description: Constructor создает стандартную матрицу 1 к 1 ABCDEF  1 0 0 1 0 0
type: docs
weight: 10
url: /ru/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Constructor создает стандартную матрицу 1 к 1: [ABCDEF] = [1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

### Примеры

```csharp
Matrix m = new Matrix();
```

### Смотрите также

* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Constructor принимает матрицу со следующим представлением массива: [ABCDEF]

```csharp
public Matrix(double[] matrixArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | Double[] | Массив данных матрицы. |

### Примеры

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Смотрите также

* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Constructor принимает матрицу со следующим представлением массива: [ABCDEF]

```csharp
public Matrix(float[] matrixArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | Single[] | Массив данных матрицы. |

### Смотрите также

* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Constructor принимает матрицу для создания копии

```csharp
public Matrix(Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | Матричный объект. |

### Смотрите также

* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Инициализирует матрицу преобразования с указанными коэффициентами.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Double | Значение матрицы. |
| b | Double | Значение матрицы B. |
| c | Double | Значение матрицы С. |
| d | Double | Значение матрицы D. |
| e | Double | Значение матрицы E. |
| f | Double | Значение F-матрицы. |

### Примеры

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Смотрите также

* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
