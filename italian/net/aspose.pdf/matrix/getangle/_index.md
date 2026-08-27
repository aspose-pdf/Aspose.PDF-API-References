---
title: "Matrix.GetAngle"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Matrix metodo. Converte la rotazione in gradi dell'angolo"
type: docs
weight: 240
url: /it/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle method

Traduce la rotazione in angolo (gradi)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotazione | Rotazione | Valore di rotazione. |

### Valore di ritorno

Valore dell'angolo.

## Esempi

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Vedi anche

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


