---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Metodo Matrix3D. Traduce la rotazione in gradi angolari
type: docs
weight: 180
url: /it/net/aspose.pdf/matrix3d/getangle/
---
## Metodo Matrix3D.GetAngle

Traduce la rotazione in angolo (gradi)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotation | Rotation | Valore di rotazione. |

### Valore di ritorno

Valore dell'angolo.

## Esempi

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Vedi anche

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)