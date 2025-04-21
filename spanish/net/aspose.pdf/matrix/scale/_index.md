---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Escala x e y con la matriz utilizando la siguiente fórmula x1 = Ax + Cy; y1 = Bx + Dy
type: docs
weight: 190
url: /es/net/aspose.pdf/matrix/scale/
---
## Escalar(double, double, out double, out double)

Escala x e y con la matriz utilizando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Doble | Coordenada X de entrada |
| y | Doble | Coordenada Y de entrada |
| x1 | Doble& | Coordenada X de salida |
| y1 | Doble& | Coordenada Y de salida |

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Escalar(double, double, Matrix)

Aplica escalado a la matriz dada.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | Doble | El factor de escalado para el eje X. |
| sy | Doble | El factor de escalado para el eje Y. |
| source | Matrix | La matriz a escalar. |

### Valor de Retorno

Una nueva matriz que es el resultado de escalar la matriz de origen.

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)