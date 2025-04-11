---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Método Matrix3D. Traduz a rotação em graus de ângulo
type: docs
weight: 180
url: /pt/net/aspose.pdf/matrix3d/getangle/
---
## Método Matrix3D.GetAngle

Traduz a rotação em ângulo (graus)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rotação | Rotação | Valor de rotação. |

### Valor de Retorno

Valor do ângulo.

## Exemplos

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Veja Também

* enum [Rotação](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)