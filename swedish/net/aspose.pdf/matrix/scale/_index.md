---
title: "Matrix.Scale"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix-metod. Skalar x och y med matrisen med hjälp av följande formel x1  Ax  Cy y1  Bx  Dy"
type: docs
weight: 190
url: /sv/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Skalar x och y med matrisen med hjälp av följande formel: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Double | Indata X-koordinat |
| y | Double | Indata Y-koordinat |
| x1 | Double& | Utdata X-koordinat |
| y1 | Double& | Utdata Y-koordinat |

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Tillämpar skalning på den givna matrisen.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | Double | Skalfaktorn för X-axeln. |
| sy | Double | Skalfaktorn för Y-axeln. |
| källa | Matrix | Matrisen som ska skalas. |

### Returvärde

En ny matris som är resultatet av att skala källmatrisen.

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


