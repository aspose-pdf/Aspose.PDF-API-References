---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Метод матрицы. Создает матрицу для заданного угла поворота
type: docs
weight: 20
url: /ru/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Создает матрицу для заданного угла поворота.

```csharp
public static Matrix Rotation(double alpha)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Double | Угол поворота в радианах. |

### Возвращаемое значение

Матрица преобразования.

## Примеры

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### См. также

* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Создает матрицу для заданного поворота.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | Rotation | Поворот. Допустимые значения: None, on90, on180, on270 |

### Возвращаемое значение

Матрица с поворотом.

### См. также

* перечисление [Rotation](../../rotation/)
* класс [Matrix](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)