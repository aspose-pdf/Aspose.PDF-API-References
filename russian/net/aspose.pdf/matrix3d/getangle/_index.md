---
title: "Matrix3D.GetAngle"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Matrix3D. Переводит вращение в градусы"
type: docs
weight: 180
url: /ru/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle method

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
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


