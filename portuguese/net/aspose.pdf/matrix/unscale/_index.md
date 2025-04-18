---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Método da matriz. Redimensiona x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula x = D  x1 - C  y1 / A  D - C  B; y = A  y1 - B  x1 / A  D - C  B;
type: docs
weight: 220
url: /pt/net/aspose.pdf/matrix/unscale/
---
## Método Matrix.UnScale

Redimensiona x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | Double | Coordenada X de entrada |
| y1 | Double | Coordenada Y de entrada |
| x | Double& | Coordenada X de saída |
| y | Double& | Coordenada Y de saída |

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)