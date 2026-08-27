---
title: "Matrix.Rotation"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix. Создаёт матрицу для заданного угла вращения"
type: docs
weight: 20
url: /ru/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Создаёт матрицу для заданного угла вращения.

```csharp
public static Matrix Rotation(double alpha)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Double | Угол вращения в радианах. |

### Возвращаемое значение

Матрица преобразования.

## Примеры

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### См. также

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Создает матрицу для заданного вращения.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| вращение | Rotation | Вращение. Допустимые значения: None, on90, on180, on270 |

### Возвращаемое значение

Матрица с вращением.

### См. также

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


