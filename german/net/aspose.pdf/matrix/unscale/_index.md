---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Methode. Skaliert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück x = D  x1 - C  y1 / A  D - C  B; y = A y1 - B x1 / A D - C B;
type: docs
weight: 220
url: /de/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale-Methode

Skaliert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | Double | Eingabe-X-Koordinate |
| y1 | Double | Eingabe-Y-Koordinate |
| x | Double& | Ausgabe-X-Koordinate |
| y | Double& | Ausgabe-Y-Koordinate |

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)