---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix-metod. Översätter rotation till vinkelgrader
type: docs
weight: 240
url: /sv/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle metod

Översätter rotation till vinkel (grader)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotation | Rotation | Rotationsvärde. |

### Returvärde

Värde för vinkel.

## Exempel

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Se Även

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)