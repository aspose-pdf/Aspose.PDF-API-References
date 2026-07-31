---
title: "Matrix.UnScale"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Matrix. Riporta indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B"
type: docs
weight: 220
url: /it/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale method

Ripristina x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | Double | Coordinata X di input |
| y1 | Double | Coordinata Y di input |
| x | Double& | Coordinata X di output |
| y | Double& | Coordinata Y di output |

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


