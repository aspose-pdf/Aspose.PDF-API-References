---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D-Methode. Übersetzt Rotation in Winkelgrade
type: docs
weight: 180
url: /de/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle-Methode

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
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)