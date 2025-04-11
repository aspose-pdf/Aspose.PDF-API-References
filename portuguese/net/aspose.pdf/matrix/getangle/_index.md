---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Método Matrix. Transforma rotação em graus de ângulo
type: docs
weight: 240
url: /pt/net/aspose.pdf/matrix/getangle/
---
## Método Matrix.GetAngle

Transforma rotação em ângulo (graus)

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
* class [Matriz](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)