---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Matrix-metod. Skalar tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B
type: docs
weight: 220
url: /sv/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale metod

Skalar tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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