---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Método Matrix3D. Traduce la rotación en grados de ángulo
type: docs
weight: 180
url: /es/net/aspose.pdf/matrix3d/getangle/
---
## Método Matrix3D.GetAngle

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
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)