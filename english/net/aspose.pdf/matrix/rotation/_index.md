---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Matrix method. Creates matrix for given rotation angle
type: docs
weight: 20
url: /net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Creates matrix for given rotation angle.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alpha | Double | Rotation angle in radians. |

### Return Value

Transformation matrix.

## Examples

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Creates matrix for given rotation.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation. Valid values are: None, on90, on180, on270 |

### Return Value

Matrix with rotation.

### See Also

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


