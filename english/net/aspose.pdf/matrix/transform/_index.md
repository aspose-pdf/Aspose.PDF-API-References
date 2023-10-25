---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Matrix method. Transforms point using this matrix
type: docs
weight: 190
url: /net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transforms point using this matrix.

```csharp
public Point Transform(Point p)
```

| Parameter | Type | Description |
| --- | --- | --- |
| p | Point | Point which will be transformed. |

### Return Value

Transformation result.

## Examples

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### See Also

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

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

## Examples

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Rectangle to be transformed. |

### Return Value

Transformed rectangle.

## Examples

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### See Also

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


