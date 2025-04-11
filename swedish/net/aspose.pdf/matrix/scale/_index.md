---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Matrix-metod. Skalar x och y med matrisen med följande formel x1  Ax  Cy y1  Bx  Dy
type: docs
weight: 190
url: /sv/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Skalar x och y med matrisen med följande formel: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Dubbel | Indata X-koordinat |
| y | Dubbel | Indata Y-koordinat |
| x1 | Dubbel& | Utdata X-koordinat |
| y1 | Dubbel& | Utdata Y-koordinat |

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Tillämpa skalning på den angivna matrisen.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | Dubbel | Skalningsfaktorn för X-axeln. |
| sy | Dubbel | Skalningsfaktorn för Y-axeln. |
| source | Matrix | Matrisen som ska skalas. |

### Returvärde

En ny matris som är resultatet av att skala källmatrisen.

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)