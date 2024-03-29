---
title: Matrix
second_title: Aspose.PDF för .NET API Referens
description: Klass representerar transformationsmatris.
type: docs
weight: 4740
url: /sv/net/aspose.pdf/matrix/
---
## Matrix class

Klass representerar transformationsmatris.

```csharp
public sealed class Matrix
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Matrix](matrix#constructor)() | Constructor skapar standard 1 till 1 matris: [ ABCDEF ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix#constructor_3)(double[]) | Constructor accepterar en matris med följande arrayrepresentation: [ ABCDEF ] |
| [Matrix](matrix#constructor_4)(float[]) | Constructor accepterar en matris med följande arrayrepresentation: [ ABCDEF ] |
| [Matrix](matrix#constructor_1)(Matrix) | Constructor accepterar en matris för att skapa en copy |
| [Matrix](matrix#constructor_2)(double, double, double, double, double, double) | Initierar transformationsmatris med specificerade koefficienter. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [A](../../aspose.pdf/matrix/a) { get; set; } | En medlem av transformationsmatrisen. |
| [B](../../aspose.pdf/matrix/b) { get; set; } | B medlem av transformationsmatrisen. |
| [C](../../aspose.pdf/matrix/c) { get; set; } | C medlem av transformationsmatrisen. |
| [D](../../aspose.pdf/matrix/d) { get; set; } | D medlem av transformationsmatrisen. |
| [Data](../../aspose.pdf/matrix/data) { get; } | Hämtar data från Matrix som array. |
| [E](../../aspose.pdf/matrix/e) { get; set; } | E medlem av transformationsmatrisen. |
| [Elements](../../aspose.pdf/matrix/elements) { get; } | Element i matrisen. |
| [F](../../aspose.pdf/matrix/f) { get; set; } | F medlem av transformationsmatrisen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation_1)(double) | Skapar matris för given rotationsvinkel. |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation)(Rotation) | Skapar matris för given rotation. |
| static [Skew](../../aspose.pdf/matrix/skew)(double, double) | Skapar matris för given rotationsvinkel. |
| [Add](../../aspose.pdf/matrix/add)(Matrix) | Lägger till matris till annan matris. |
| override [Equals](../../aspose.pdf/matrix/equals)(object) | Jämför matris med andra objekt. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode)() | Hash-kod för objekt. |
| [Multiply](../../aspose.pdf/matrix/multiply)(Matrix) | Multiplicerar matrisen med annan matris. |
| [Reverse](../../aspose.pdf/matrix/reverse)() | Beräknar omvänd matris. |
| override [ToString](../../aspose.pdf/matrix/tostring)() | Returnerar textrepresentation av matrisen. |
| [Transform](../../aspose.pdf/matrix/transform#transform)(Point) | Transformerar punkt med denna matris. |
| [Transform](../../aspose.pdf/matrix/transform#transform_1)(Rectangle) | Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras gränsande rektangel. |
| static [GetAngle](../../aspose.pdf/matrix/getangle)(Rotation) | Omvandlar rotation till vinkel (grader) |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
