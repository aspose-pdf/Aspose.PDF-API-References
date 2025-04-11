---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Метод Matrix3D. Переводит вращение в градусы угла
type: docs
weight: 180
url: /ru/net/aspose.pdf/matrix3d/getangle/
---
## Метод Matrix3D.GetAngle

Переводит вращение в угол (градусы)

```csharp
public static double GetAngle(Rotation rotation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | Rotation | Значение вращения. |

### Возвращаемое значение

Значение угла.

## Примеры

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### См. также

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)