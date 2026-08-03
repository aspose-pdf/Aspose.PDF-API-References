---
title: "Matrix.UnTransform"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix metod. Omvandlar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /sv/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

Transformerar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | Double | Indata X-koordinat |
| y1 | Double | Indata Y-koordinat |
| x | Double& | Utdata X-koordinat |
| y | Double& | Utdata Y-koordinat |

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


