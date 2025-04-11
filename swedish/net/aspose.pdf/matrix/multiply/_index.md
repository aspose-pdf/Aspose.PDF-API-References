---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Matrixmetod. Multiplicerar matrisen med en annan matris
type: docs
weight: 170
url: /sv/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply metod

Multiplicerar matrisen med en annan matris.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | Matrix | Multiplikator matris. |

### Returvärde

Resultat av multiplikationen.

## Exempel

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)