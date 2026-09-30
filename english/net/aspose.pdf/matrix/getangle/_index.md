---
title: "Matrix.GetAngle"
linktitle: "GetAngle"
articleTitle: "GetAngle"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Transaltes rotation into angle (degrees)"
type: docs
weight: 130
url: "/net/aspose.pdf/matrix/getangle/"
product_version: "26.9.0"
---
## Matrix.GetAngle method

Transaltes rotation into angle (degrees)

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

* enum [Rotation](../../../aspose.pdf/rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

