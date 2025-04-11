---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Méthode de matrice. Crée une matrice pour un angle de rotation donné
type: docs
weight: 20
url: /fr/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Crée une matrice pour un angle de rotation donné.

```csharp
public static Matrix Rotation(double alpha)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | Double | Angle de rotation en radians. |

### Valeur de retour

Matrice de transformation.

## Exemples

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Crée une matrice pour une rotation donnée.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation. Les valeurs valides sont : None, on90, on180, on270 |

### Valeur de retour

Matrice avec rotation.

### Voir aussi

* enum [Rotation](../../rotation/)
* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)