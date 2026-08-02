---
title: "Matrix.GetAngle"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix. Переводит вращение в градусы угла"
type: docs
weight: 240
url: /ru/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle method

Преобразует вращение в угол (градусы)

```csharp
public static double GetAngle(Rotation rotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| вращение | Rotation | Значение вращения. |

### Возвращаемое значение

Значение угла.

## Примеры

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### См. также

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


