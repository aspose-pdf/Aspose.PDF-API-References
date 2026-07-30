---
title: "Matrix.Rotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Matrix. Crée une matrice pour l'angle de rotation donné"
type: docs
weight: 20
url: /fr/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Crée une matrice pour l'angle de rotation donné.

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

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Crée une matrice pour la rotation donnée.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Rotation. Les valeurs valides sont : None, on90, on180, on270 |

### Valeur de retour

Matrice avec rotation.

### Voir aussi

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


