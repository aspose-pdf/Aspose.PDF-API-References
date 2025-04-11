---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Méthode Matrix. Traduit la rotation en degrés d'angle
type: docs
weight: 240
url: /fr/net/aspose.pdf/matrix/getangle/
---
## Méthode Matrix.GetAngle

Traduit la rotation en angle (degrés)

```csharp
public static double GetAngle(Rotation rotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rotation | Rotation | Valeur de rotation. |

### Valeur de retour

Valeur de l'angle.

## Exemples

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Voir aussi

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)