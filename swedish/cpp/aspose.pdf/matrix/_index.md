---
title: "Aspose::Pdf::Matrix-klass"
linktitle: "Matrix"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix-klass. Klassen representerar transformationsmatris i C++."
type: docs
weight: 10900
url: /sv/cpp/aspose.pdf/matrix/
---
## Matrix class


Klassen representerar transformationsmatris.

```cpp
class Matrix : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix\>\&) | Lägger till matris till en annan matris. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Jämför matris med ett annat objekt. |
| [get_A](./get_a/)() | En medlem i transformationsmatrisen. |
| [get_B](./get_b/)() | B-medlem i transformationsmatrisen. |
| [get_C](./get_c/)() | C-medlem i transformationsmatrisen. |
| [get_D](./get_d/)() | D-medlem i transformationsmatrisen. |
| [get_Data](./get_data/)() const | Hämtar data från [Matrix](./) som array. |
| [get_E](./get_e/)() | E-medlem i transformationsmatrisen. |
| [get_Elements](./get_elements/)() | Element i matrisen. |
| [get_F](./get_f/)() | F-medlem i transformationsmatrisen. |
| static [GetAngle](./getangle/)(Aspose::Pdf::Rotation) | Översätter rotation till vinkel (grader) |
| [GetFlipMatrix](./getflipmatrix/)() | Hämtar vändningsmatrisen. |
| [GetHashCode](./gethashcode/)() const override | Hash-kod för objekt. |
| [Matrix](./matrix/)() | Konstruktor skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]. |
| [Matrix](./matrix/)(const System::ArrayPtr\<double\>\&) | Konstruktor accepterar en matris med följande arrayrepresentation: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::Details::ArrayView\<float\>\&) | Konstruktor accepterar en matris med följande arrayrepresentation: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::SharedPtr\<Matrix\>\&) | Konstruktor accepterar en matris för att skapa en kopia. |
| [Matrix](./matrix/)(double, double, double, double, double, double) | Initierar transformationsmatris med angivna koefficienter. |
| [Multiply](./multiply/)(const System::SharedPtr\<Matrix\>\&) | Multiplicerar matrisen med en annan matris. |
| [Reverse](./reverse/)() | Beräknar omvänd matris. |
| static [Rotation](./rotation/)(double) | Skapar matris för given rotationsvinkel. |
| static [Rotation](./rotation/)(Aspose::Pdf::Rotation) | Skapar matris för given rotation. |
| [Scale](./scale/)(double, double, double\&, double\&) | Skalar x och y med matrisen med följande formel: x1 = A*x + C*y; y1 = B*x + D*y;. |
| static [Scale](./scale/)(double, double, const System::SharedPtr\<Matrix\>\&) | Tillämpar skalning på den givna matrisen. |
| [set_A](./set_a/)(double) | En medlem i transformationsmatrisen. |
| [set_B](./set_b/)(double) | B-medlem i transformationsmatrisen. |
| [set_C](./set_c/)(double) | C-medlem i transformationsmatrisen. |
| [set_D](./set_d/)(double) | D-medlem i transformationsmatrisen. |
| [set_E](./set_e/)(double) | E-medlem i transformationsmatrisen. |
| [set_F](./set_f/)(double) | F-medlem i transformationsmatrisen. |
| static [Skew](./skew/)(double, double) | Skapar matris för given rotationsvinkel. |
| [ToString](./tostring/)() const override | Returnerar textrepresentation av matrisen. |
| [Transform](./transform/)(const System::SharedPtr\<Point\>\&) | Transformerar punkt med denna matris. |
| [Transform](./transform/)(double, double, double\&, double\&) | Transformerar koordinater med denna matris. |
| [Transform](./transform/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Transformerar rektangel. Om vinkeln inte är 90 * N grader returneras omgivande rektangel. |
| static [Translate](./translate/)(double, double, const System::SharedPtr\<Matrix\>\&) | Översätter en matris med den angivna mängden i x- och y-riktning. |
| [UnScale](./unscale/)(double, double, double\&, double\&) | Skalar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);. |
| [UnTransform](./untransform/)(double, double, double\&, double\&) | Omvandlar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
