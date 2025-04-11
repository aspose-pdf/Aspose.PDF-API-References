---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix metodu. Dönmeyi açı derecelerine çevirir
type: docs
weight: 240
url: /tr/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle metodu

Dönmeyi açıya (dereceler) çevirir

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
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)