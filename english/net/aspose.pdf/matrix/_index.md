---
title: "Matrix Class"
linktitle: "Matrix"
articleTitle: "Matrix"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Matrix class. Class represents transformation matrix."
type: docs
weight: 1830
url: "/net/aspose.pdf/matrix/"
keywords: "Matrix, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Matrix class

Class represents transformation matrix.

```csharp
public sealed class Matrix
```

## Constructors

| Name | Description |
| --- | --- |
| [Matrix](./matrix/#constructor)() | Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](./matrix/#constructor_1)(double[]) | Constructor accepts a matrix with following array representation: [ A B C D E F ] |
| [Matrix](./matrix/#constructor_2)(float[]) | Constructor accepts a matrix with following array representation: [ A B C D E F ] |
| [Matrix](./matrix/#constructor_3)(Matrix) | Constructor accepts a matrix to create a copy |
| [Matrix](./matrix/#constructor_4)(double, double, double, double, double, double) | Initializes transformation matrix with specified coefficients. |

## Properties

| Name | Description |
| --- | --- |
| [A](./a/) { get; set; } | A member of the transformation matrix. |
| [B](./b/) { get; set; } | B member of the transformation matrix. |
| [C](./c/) { get; set; } | C member of the transformation matrix. |
| [D](./d/) { get; set; } | D member of the transformation matrix. |
| [Data](./data/) { get; } | Gets data of Matrix as array. |
| [E](./e/) { get; set; } | E member of the transformation matrix. |
| [Elements](./elements/) { get; } | Elements of the matrix. |
| [F](./f/) { get; set; } | F member of the transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(Matrix) | Adds matrix to other matrix. |
| override [Equals](./equals/)(object) | Compares matrix agains other object. |
| static [GetAngle](./getangle/)(Rotation) | Transaltes rotation into angle (degrees) |
| [GetFlipMatrix](./getflipmatrix/)() | Gets the flipping matrix. |
| override [GetHashCode](./gethashcode/)() | Hash-code for object. |
| [Multiply](./multiply/)(Matrix) | Multiplies the matrix by other matrix. |
| [Reverse](./reverse/)() | Calculates reverse matrix. |
| static [Rotation](./rotation/)(double) | Creates matrix for given rotation angle. |
| static [Rotation](./rotation/)(Rotation) | Creates matrix for given rotation. |
| static [Scale](./scale/)(double, double, Matrix) | Applies scaling to the given matrix. |
| [Scale](./scale/)(double, double, out double, out double) | Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y; |
| static [Skew](./skew/)(double, double) | Creates matrix for given rotation angle. |
| override [ToString](./tostring/)() | Returns text reporesentation of the matrix. |
| [Transform](./transform/)(Point) | Transforms point using this matrix. |
| [Transform](./transform/)(Rectangle) | Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned. |
| [Transform](./transform/)(double, double, out double, out double) | Transforms coordinates using this matrix. |
| static [Translate](./translate/)(double, double, Matrix) | Translates a matrix by the specified amount in the x and y direction. |
| [UnScale](./unscale/)(double, double, out double, out double) | Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](./untransform/)(double, double, out double, out double) | Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

