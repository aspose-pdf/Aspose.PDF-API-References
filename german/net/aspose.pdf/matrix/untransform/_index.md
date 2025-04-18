---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Methode. Transformiert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück x = D  x1 - C  y1 + C  F / A  D - C  B; y = A  y1 - B  x1 + B  E / A  D - C  B.
type: docs
weight: 230
url: /de/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform-Methode

Transformiert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | Double | Eingabe X-Koordinate |
| y1 | Double | Eingabe Y-Koordinate |
| x | Double& | Ausgabe X-Koordinate |
| y | Double& | Ausgabe Y-Koordinate |

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)