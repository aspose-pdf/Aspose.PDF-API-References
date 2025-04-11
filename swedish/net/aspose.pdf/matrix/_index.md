---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix klass. Klassen representerar transformationsmatris
type: docs
weight: 6920
url: /sv/net/aspose.pdf/matrix/
---
## Matrix klass

Klassen representerar transformationsmatris.

```csharp
public sealed class Matrix
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Matrix](matrix/#constructor)() | Konstruktör skapar standard 1 till 1 matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Konstruktör accepterar en matris med följande arrayrepresentation: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Konstruktör accepterar en matris med följande arrayrepresentation: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Konstruktör accepterar en matris för att skapa en kopia |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Initierar transformationsmatris med angivna koefficienter. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | A medlem av transformationsmatrisen. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | B medlem av transformationsmatrisen. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | C medlem av transformationsmatrisen. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | D medlem av transformationsmatrisen. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Hämtar data av Matrix som array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | E medlem av transformationsmatrisen. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elementen av matrisen. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | F medlem av transformationsmatrisen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Skapar matris för angiven rotationsvinkel. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Skapar matris för angiven rotation. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Tillämpa skalning på den angivna matrisen. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Skapar matris för angiven rotationsvinkel. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Översätter en matris med den angivna mängden i x- och y-riktning. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Lägger till matris till en annan matris. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Jämför matris mot ett annat objekt. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Hämtar den vändande matrisen. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Hash-kod för objekt. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multiplicerar matrisen med en annan matris. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Beräknar den omvända matrisen. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Skalar x och y med matrisen med hjälp av följande formel: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Returnerar textrepresentation av matrisen. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transformera punkt med hjälp av denna matris. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transformera rektangel. Om vinkeln inte är 90 * N grader returneras den begränsande rektangeln. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transformera koordinater med hjälp av denna matris. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Skalar tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transformera tillbaka x1 och y1 och returnerar x och y före matristransformationen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Översätter rotation till vinkel (grader) |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)