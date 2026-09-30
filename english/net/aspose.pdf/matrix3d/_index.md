---
title: "Matrix3D Class"
linktitle: "Matrix3D"
articleTitle: "Matrix3D"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Matrix3D class. Class represents transformation matrix."
type: docs
weight: 1840
url: "/net/aspose.pdf/matrix3d/"
keywords: "Matrix3D, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Matrix3D class

Class represents transformation matrix.

```csharp
public sealed class Matrix3D
```

## Constructors

| Name | Description |
| --- | --- |
| [Matrix3D](./matrix3d/#constructor)() | Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](./matrix3d/#constructor_1)(double[]) | Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](./matrix3d/#constructor_2)(Matrix3D) | Constructor accepts a matrix to create a copy |
| [Matrix3D](./matrix3d/#constructor_3)(double, double, double, double, double, double, double, double, double, double, double, double) | Initializes transformation matrix with specified coefficients. |

## Properties

| Name | Description |
| --- | --- |
| [A](./a/) { get; set; } | A member of the transformation matrix. |
| [B](./b/) { get; set; } | B member of the transformation matrix. |
| [C](./c/) { get; set; } | C member of the transformation matrix. |
| [D](./d/) { get; set; } | D member of the transformation matrix. |
| [E](./e/) { get; set; } | E member of the transformation matrix. |
| [F](./f/) { get; set; } | F member of the transformation matrix. |
| [G](./g/) { get; set; } | G member of the transformation matrix. |
| [H](./h/) { get; set; } | H member of the transformation matrix. |
| [I](./i/) { get; set; } | I member of the transformation matrix. |
| [Tx](./tx/) { get; set; } | Tx member of the transformation matrix. |
| [Ty](./ty/) { get; set; } | Ty member of the transformation matrix. |
| [Tz](./tz/) { get; set; } | Tz member of the transformation matrix. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(Matrix3D) | Adds matrix to other matrix. |
| override [Equals](./equals/)(object) | Compares matrix against other object. |
| static [GetAngle](./getangle/)(Rotation) | Translates rotation into angle (degrees) |
| override [GetHashCode](./gethashcode/)() | Hash-code for object. |
| override [ToString](./tostring/)() | Returns text representation of the matrix. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

