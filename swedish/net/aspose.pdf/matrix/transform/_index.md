---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Matrixmetod. Transformerar punkt med hjälp av denna matris
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
| p | Punkt | Punkten som kommer att transformeras. |

### Returvärde

Transformationsresultat.

## Exempel

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Se Även

* klass [Point](../../point/)
* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transformerar koordinater med hjälp av denna matris.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Dubbel | X-koordinat. |
| y | Dubbel | Y-koordinat. |
| x1 | Dubbel& | Transformerad X-koordinat. |
| y1 | Dubbel& | Transformerad Y-koordinat. |

## Exempel

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras den begränsande rektangeln.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rektangel | Rektangeln som ska transformeras. |

### Returvärde

Transformerad rektangel.

## Exempel

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Se Även

* klass [Rectangle](../../rectangle/)
* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)