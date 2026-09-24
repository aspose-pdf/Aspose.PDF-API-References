---
title: "Matrix Class"
linktitle: "Matrix"
articleTitle: "Matrix"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Matrix class. Class represents transformation matrix."
type: docs
weight: 1870
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
| [Matrix](./matrix/#constructor) | Constructor. |
| [Matrix](./matrix/#constructor_1)(*double[]*) | Constructor. |
| [Matrix](./matrix/#constructor_2)(*float[]*) | Constructor. |
| [Matrix](./matrix/#constructor_3)(*[Matrix](../../aspose.pdf/matrix/)*) | Constructor. |
| [Matrix](./matrix/#constructor_4)(*double, double, double, double, double, double*) | Initializes transformation matrix with specified coefficients. |

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
| [Add](./add/)(*Matrix*) | Adds matrix to other matrix. |
| [Equals](./equals/)(*object*) | Compares matrix agains other object. |
| [GetAngle](./getangle/)(*Rotation*) | Transaltes rotation into angle (degrees). |
| [GetFlipMatrix](./getflipmatrix/) | Gets the flipping matrix. |
| [GetHashCode](./gethashcode/) | Hash-code for object. |
| [Multiply](./multiply/)(*Matrix*) | Multiplies the matrix by other matrix. |
| [Reverse](./reverse/) | Calculates reverse matrix. |
| [Rotation](./rotation/)(*double*) | Creates matrix for given rotation angle. |
| [Rotation](./rotation/)(*Rotation*) | Creates matrix for given rotation. |
| [Scale](./scale/)(*double, double, Matrix*) | Applies scaling to the given matrix. |
| [Scale](./scale/)(*double, double, double, double*) |  |
| [Skew](./skew/)(*double, double*) | Creates matrix for given rotation angle. |
| [ToString](./tostring/) | Returns text reporesentation of the matrix. |
| [Transform](./transform/)(*Point*) | Transforms point using this matrix. |
| [Transform](./transform/)(*Rectangle*) | Transformes rectangle. |
| [Transform](./transform/)(*double, double, double, double*) |  |
| [Translate](./translate/)(*double, double, Matrix*) | Translates a matrix by the specified amount in the x and y direction. |
| [UnScale](./unscale/)(*double, double, double, double*) |  |
| [UnTransform](./untransform/)(*double, double, double, double*) |  |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

