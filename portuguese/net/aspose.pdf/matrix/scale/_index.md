---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Método da matriz. Escala x e y com a matriz usando a seguinte fórmula x1 = Ax + Cy; y1 = Bx + Dy
type: docs
weight: 190
url: /pt/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Escala x e y com a matriz usando a seguinte fórmula: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | Double | Coordenada X de entrada |
| y | Double | Coordenada Y de entrada |
| x1 | Double& | Coordenada X de saída |
| y1 | Double& | Coordenada Y de saída |

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Aplica escalonamento à matriz dada.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sx | Double | O fator de escalonamento para o eixo X. |
| sy | Double | O fator de escalonamento para o eixo Y. |
| source | Matrix | A matriz a ser escalada. |

### Valor de Retorno

Uma nova matriz que é o resultado do escalonamento da matriz de origem.

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)