---
title: "Matrix3D.Matrix3D"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор Matrix3D. Конструктор создает стандартную матрицу 1 к 1  A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0"
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

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Конструктор принимает матрицу со следующим представлением массива: [ A B C D E F G H I Tx Ty Tz]

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

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Инициализирует матрицу преобразования с указанными коэффициентами.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Double | Значение матрицы. |
| b | Double | Значение B матрицы. |
| c | Double | Значение C матрицы. |
| d | Double | Значение D матрицы. |
| e | Double | Значение E матрицы. |
| f | Double | Значение матрицы F. |
| g | Double | Значение G в матрице. |
| h | Double | Значение H в матрице. |
| i | Double | Значение I в матрице. |
| tx | Double | Значение TX в матрице. |
| ty | Double | Значение TY в матрице. |
| tz | Double | Значение TZ в матрице. |

## Примеры

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### См. также

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


