---
title: "Matrix.Transform"
linktitle: "Transform"
articleTitle: "Transform"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Transforms point using this matrix."
type: docs
weight: 160
url: "/net/aspose.pdf/matrix/transform/"
product_version: "26.9.0"
---
## Transform([Point](../../../aspose.pdf/point/)) {#transform}

Transforms point using this matrix.

```csharp
public Point Transform(Point p)
```

| Parameter | Type | Description |
| --- | --- | --- |
| p | Point | Point which will be transformed. |

### Return Value

Transformation result.

### See Also

* class [Point](../../../aspose.pdf/point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_1}

Transforms coordinates using this matrix.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | X coordinate. |
| y | Double | Y coordinate. |
| x1 | Double& | Transformed X coordinate. |
| y1 | Double& | Transformed Y coordinate. |

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform([Rectangle](../../../aspose.pdf.drawing/rectangle/)) {#transform_2}

Transformes rectangle.
 If angle is not 90 * N degrees then bounding rectangle is returned.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Rectangle to be transformed. |

### Return Value

Transformed rectangle.

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

