---
title: Transform
second_title: Aspose.PDF för .NET API Referens
description: Transformerar punkt med denna matris.
type: docs
weight: 180
url: /sv/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transformerar punkt med denna matris.

```csharp
public Point Transform(Point p)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Point | Punkt som kommer att förvandlas. |

### Returvärde

Förvandlingsresultat.

### Exempel

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Se även

* class [Point](../../point)
* class [Matrix](../../matrix)
* namnutrymme [Aspose.Pdf](../../matrix)
* hopsättning [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras gränsande rektangel.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangel som ska omvandlas. |

### Returvärde

Transformerad rektangel.

### Exempel

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Se även

* class [Rectangle](../../rectangle)
* class [Matrix](../../matrix)
* namnutrymme [Aspose.Pdf](../../matrix)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
