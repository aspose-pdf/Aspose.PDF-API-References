---
title: "Klass Matrix"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Matrix-klass. Klassen representerar en transformationsmatris"
type: docs
weight: 7060
url: /sv/net/aspose.pdf/matrix/
---
## Matrix class

Klassen representerar en transformationsmatris.

```csharp
public sealed class Matrix
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Matrix](matrix/#constructor)() | Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Konstruktorn accepterar en matris för att skapa en kopia |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Initierar transformationsmatris med angivna koefficienter. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | A-medlem i transformationsmatrisen. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | B-medlem i transformationsmatrisen. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | C-medlem i transformationsmatrisen. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | D-medlem i transformationsmatrisen. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Hämtar data från Matrix som array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | E-medlem i transformationsmatrisen. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Element i matrisen. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | F-medlem i transformationsmatrisen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Skapar matris för given rotationsvinkel. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Skapar matris för given rotation. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Tillämpar skalning på den givna matrisen. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Skapar matris för given rotationsvinkel. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Översätter en matris med den angivna mängden i x- och y-riktning. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Lägger till matris till en annan matris. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Jämför matrisen med ett annat objekt. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Hämtar den vändande matrisen. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Hashkod för objekt. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multiplicerar matrisen med en annan matris. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Beräknar omvänd matris. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Skalar x och y med matrisen med hjälp av följande formel: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Returnerar textrepresentation av matrisen. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transformerar punkt med hjälp av denna matris. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras omgivande rektangel. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transformerar koordinater med hjälp av denna matris. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Skalar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transformerar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Översätter rotation till vinkel (grader) |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


