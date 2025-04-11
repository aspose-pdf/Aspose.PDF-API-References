---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Metodo Matrix. Trasforma la rotazione in gradi angolari
type: docs
weight: 240
url: /it/net/aspose.pdf/matrix/getangle/
---
## Metodo Matrix.GetAngle

Trasforma la rotazione in angolo (gradi)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotation | Rotation | Valore di rotazione. |

### Valore di Ritorno

Valore dell'angolo.

## Esempi

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Vedi Anche

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)