---
title: "Matrix3D.GetAngle"
linktitle: "GetAngle"
articleTitle: "GetAngle"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix3D method. Translates rotation into angle (degrees)"
type: docs
weight: 70
url: "/net/aspose.pdf/matrix3d/getangle/"
product_version: "26.9"
---
## Matrix3D.GetAngle method

Translates rotation into angle (degrees)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation value. |

### Return Value

Angle value.

## Examples

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### See Also

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

