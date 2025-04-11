---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Matrix-metod. Transformerar tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B
type: docs
weight: 230
url: /sv/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform metod

Transformerar tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | Double | Indata X-koordinat |
| y1 | Double | Indata Y-koordinat |
| x | Double& | Utdata X-koordinat |
| y | Double& | Utdata Y-koordinat |

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)