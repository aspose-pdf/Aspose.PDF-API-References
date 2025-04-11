---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Méthode Matrix3D. Traduit la rotation en degrés d'angle
type: docs
weight: 180
url: /fr/net/aspose.pdf/matrix3d/getangle/
---
## Méthode Matrix3D.GetAngle

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
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)