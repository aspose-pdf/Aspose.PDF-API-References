---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Methode. Transformiert Punkt mit dieser Matrix
type: docs
weight: 210
url: /de/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transformiert Punkt mit dieser Matrix.

```csharp
public Point Transform(Point p)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | Punkt | Punkt, der transformiert wird. |

### Rückgabewert

Transformationsergebnis.

## Beispiele

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Siehe auch

* Klasse [Point](../../point/)
* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transformiert Koordinaten mit dieser Matrix.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Double | X-Koordinate. |
| y | Double | Y-Koordinate. |
| x1 | Double& | Transformierte X-Koordinate. |
| y1 | Double& | Transformierte Y-Koordinate. |

## Beispiele

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transformiert Rechteck. Wenn der Winkel nicht 90 * N Grad beträgt, wird das umschließende Rechteck zurückgegeben.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Rechteck, das transformiert werden soll. |

### Rückgabewert

Transformiertes Rechteck.

## Beispiele

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)