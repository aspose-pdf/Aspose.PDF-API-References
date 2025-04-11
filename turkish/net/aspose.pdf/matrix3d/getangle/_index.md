---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D metodu. Dönmeyi açı derecelerine çevirir
type: docs
weight: 180
url: /tr/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle metodu

Dönmeyi açıya (derece) çevirir

```csharp
public static double GetAngle(Rotation rotation)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotation | Rotation | Dönme değeri. |

### Dönüş Değeri

Açı değeri.

## Örnekler

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Ayrıca Bakınız

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)