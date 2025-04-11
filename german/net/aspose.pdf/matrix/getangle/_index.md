---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Methode. Übersetzt Rotation in Winkelgrade
type: docs
weight: 240
url: /de/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle-Methode

Übersetzt Rotation in Winkel (Grad)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotation | Rotation | Rotationswert. |

### Rückgabewert

Winkelwert.

## Beispiele

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Siehe auch

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)