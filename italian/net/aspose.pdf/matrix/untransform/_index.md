---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Metodo Matrix. Trasforma indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice utilizzando la seguente formula x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).
type: docs
weight: 230
url: /it/net/aspose.pdf/matrix/untransform/
---
## Metodo Matrix.UnTransform

Trasforma indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice utilizzando la seguente formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | Double | Coordinata X di input |
| y1 | Double | Coordinata Y di input |
| x | Double& | Coordinata X di output |
| y | Double& | Coordinata Y di output |

### Vedi Anche

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)