---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Metodo Matrix. Moltiplica la matrice per un'altra matrice
type: docs
weight: 170
url: /it/net/aspose.pdf/matrix/multiply/
---
## Metodo Matrix.Multiply

Moltiplica la matrice per un'altra matrice.

```csharp
public Matrix Multiply(Matrix other)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | Matrix | Matrice moltiplicatrice. |

### Valore di ritorno

Risultato della moltiplicazione.

## Esempi

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Vedi Anche

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)