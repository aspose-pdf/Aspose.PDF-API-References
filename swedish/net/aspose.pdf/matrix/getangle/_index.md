---
title: "Matrix.GetAngle"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix‑metod. Översätter rotation till vinkelgrader"
type: docs
weight: 240
url: /sv/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle method

Översätter rotation till vinkel (grader)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotation | Rotation | Rotationsvärde. |

### Returvärde

Vinkelvärde.

## Exempel

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Se även

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


