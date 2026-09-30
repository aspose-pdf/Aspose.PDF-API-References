---
title: "Matrix.Multiply"
linktitle: "Multiply"
articleTitle: "Multiply"
second_title: "Aspose.PDF for .NET API Reference"
description: "Matrix method. Multiplies the matrix by other matrix."
type: docs
weight: 140
url: "/net/aspose.pdf/matrix/multiply/"
product_version: "26.9.0"
---
## Matrix.Multiply method

Multiplies the matrix by other matrix.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Type | Description |
| --- | --- | --- |
| other | Matrix | Multiplier matrix. |

### Return Value

Result of multiplication.

## Examples

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### See Also

* class [Matrix](../../../aspose.pdf/matrix/)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

