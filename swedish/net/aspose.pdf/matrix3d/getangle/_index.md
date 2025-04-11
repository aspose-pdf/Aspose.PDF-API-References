---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D-metod. Översätter rotation till vinkelgrader
type: docs
weight: 180
url: /sv/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle metod

Översätter rotation till vinkel (grader)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotation | Rotation | Rotationsvärde. |

### Returvärde

Värde av vinkel.

## Exempel

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Se Även

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)