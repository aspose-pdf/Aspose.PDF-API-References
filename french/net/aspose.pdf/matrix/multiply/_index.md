---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Méthode de matrice. Multiplie la matrice par une autre matrice
type: docs
weight: 170
url: /fr/net/aspose.pdf/matrix/multiply/
---
## Méthode Matrix.Multiply

Multiplie la matrice par une autre matrice.

```csharp
public Matrix Multiply(Matrix other)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| other | Matrix | Matrice multiplicatrice. |

### Valeur de retour

Résultat de la multiplication.

## Exemples

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)