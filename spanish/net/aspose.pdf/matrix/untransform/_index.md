---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Transforma de vuelta x1 e y1 y devuelve x e y antes de la transformación de la matriz utilizando la siguiente fórmula x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B
type: docs
weight: 230
url: /es/net/aspose.pdf/matrix/untransform/
---
## Método Matrix.UnTransform

Transforma de vuelta x1 e y1 y devuelve x e y antes de la transformación de la matriz utilizando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | Doble | Coordenada X de entrada |
| y1 | Doble | Coordenada Y de entrada |
| x | Doble& | Coordenada X de salida |
| y | Doble& | Coordenada Y de salida |

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)