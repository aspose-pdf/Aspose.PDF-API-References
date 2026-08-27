---
title: "Matrix.Multiply"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix-metod. Multiplicerar matrisen med en annan matris"
type: docs
weight: 170
url: /sv/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

Multiplicerar matrisen med en annan matris.

```csharp
public Matrix Multiply(Matrix other)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | Matrix | Multiplikatormatris. |

### Returvärde

Resultat av multiplikation.

## Exempel

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


