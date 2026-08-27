---
title: "Matrix.Multiply"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Matrix. Multiplie la matrice par une autre matrice"
type: docs
weight: 170
url: /fr/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

Multiplie la matrice par une autre matrice.

```csharp
public Matrix Multiply(Matrix other)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| autre | Matrice | Matrice multiplicatrice. |

### Valeur de retour

Résultat de la multiplication.

## Exemples

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Voir aussi

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


