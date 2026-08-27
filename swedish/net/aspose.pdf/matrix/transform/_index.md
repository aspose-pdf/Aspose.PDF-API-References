---
title: "Matrix.Transform"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix-metod. Transformerar en punkt med hjälp av denna matris"
type: docs
weight: 210
url: /sv/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transformerar punkt med hjälp av denna matris.

```csharp
public Point Transform(Point p)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Punkt | Punkt som kommer att transformeras. |

### Returvärde

Transformationsresultat.

## Exempel

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Se även

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transformerar koordinater med hjälp av denna matris.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Double | X-koordinat. |
| y | Double | Y-koordinat. |
| x1 | Double& | Transformerad X-koordinat. |
| y1 | Double& | Transformerad Y-koordinat. |

## Exempel

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras omgivande rektangel.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangel som ska transformeras. |

### Returvärde

Transformerad rektangel.

## Exempel

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Se även

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


