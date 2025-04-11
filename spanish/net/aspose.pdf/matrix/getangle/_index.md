---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Método Matrix. Traduce la rotación en grados de ángulo
type: docs
weight: 240
url: /es/net/aspose.pdf/matrix/getangle/
---
## Método Matrix.GetAngle

Traduce la rotación en ángulo (grados)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotation | Rotation | Valor de rotación. |

### Valor de Retorno

Valor del ángulo.

## Ejemplos

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Ver También

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)