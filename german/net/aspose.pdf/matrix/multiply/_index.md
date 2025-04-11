---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Matrixmethode. Multipliziert die Matrix mit einer anderen Matrix
type: docs
weight: 170
url: /de/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply-Methode

Multipliziert die Matrix mit einer anderen Matrix.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | Matrix | Multiplikator-Matrix. |

### Rückgabewert

Ergebnis der Multiplikation.

## Beispiele

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)