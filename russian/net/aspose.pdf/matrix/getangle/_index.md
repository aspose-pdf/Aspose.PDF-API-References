---
title: GetAngle
second_title: Aspose.PDF для справочника API .NET
description: Преобразует вращение в угол градусы
type: docs
weight: 190
url: /ru/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle method

Преобразует вращение в угол (градусы)

```csharp
public static double GetAngle(Rotation rotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | Rotation | Значение вращения. |

### Возвращаемое значение

Значение угла.

### Примеры

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Смотрите также

* enum [Rotation](../../rotation)
* class [Matrix](../../matrix)
* пространство имен [Aspose.Pdf](../../matrix)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->