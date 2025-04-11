---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Methode. Skaliert x und y mit der Matrix unter Verwendung der folgenden Formel x1 = A*x + C*y; y1 = B*x + D*y
type: docs
weight: 190
url: /de/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Skaliert x und y mit der Matrix unter Verwendung der folgenden Formel: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Double | Eingangs-X-Koordinate |
| y | Double | Eingangs-Y-Koordinate |
| x1 | Double& | Ausgangs-X-Koordinate |
| y1 | Double& | Ausgangs-Y-Koordinate |

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Wendet die Skalierung auf die gegebene Matrix an.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | Double | Der Skalierungsfaktor für die X-Achse. |
| sy | Double | Der Skalierungsfaktor für die Y-Achse. |
| source | Matrix | Die zu skalierende Matrix. |

### Rückgabewert

Eine neue Matrix, die das Ergebnis der Skalierung der Quellmatrix ist.

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)