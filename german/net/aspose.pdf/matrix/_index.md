---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix-Klasse. Klasse repräsentiert die Transformationsmatrix
type: docs
weight: 6920
url: /de/net/aspose.pdf/matrix/
---
## Matrix-Klasse

Die Klasse repräsentiert die Transformationsmatrix.

```csharp
public sealed class Matrix
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Matrix](matrix/#constructor)() | Konstruktor erstellt eine Standard-1 zu 1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Konstruktor akzeptiert eine Matrix, um eine Kopie zu erstellen |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Initialisiert die Transformationsmatrix mit den angegebenen Koeffizienten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | A-Mitglied der Transformationsmatrix. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | B-Mitglied der Transformationsmatrix. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | C-Mitglied der Transformationsmatrix. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | D-Mitglied der Transformationsmatrix. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Gibt die Daten der Matrix als Array zurück. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | E-Mitglied der Transformationsmatrix. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elemente der Matrix. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | F-Mitglied der Transformationsmatrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Erstellt eine Matrix für den angegebenen Rotationswinkel. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Erstellt eine Matrix für die angegebene Rotation. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Wendet Skalierung auf die angegebene Matrix an. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Erstellt eine Matrix für den angegebenen Rotationswinkel. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Verschiebt eine Matrix um den angegebenen Betrag in x- und y-Richtung. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Fügt eine Matrix zu einer anderen Matrix hinzu. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Vergleicht die Matrix mit einem anderen Objekt. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Gibt die Umkehrmatrix zurück. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Hash-Code für das Objekt. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multipliziert die Matrix mit einer anderen Matrix. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Berechnet die Umkehrmatrix. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Skaliert x und y mit der Matrix unter Verwendung der folgenden Formel: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Gibt die textuelle Darstellung der Matrix zurück. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transformiert den Punkt mit dieser Matrix. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transformiert das Rechteck. Wenn der Winkel nicht 90 * N Grad beträgt, wird das umschließende Rechteck zurückgegeben. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transformiert die Koordinaten mit dieser Matrix. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Skaliert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transformiert x1 und y1 zurück und gibt x und y vor der Matrixtransformation unter Verwendung der folgenden Formel zurück: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Übersetzt die Rotation in einen Winkel (Grad) |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)