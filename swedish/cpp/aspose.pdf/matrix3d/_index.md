---
title: "Aspose::Pdf::Matrix3D class"
linktitle: "Matrix3D"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Matrix3D class. Klassen representerar en transformationsmatris i C++."
type: docs
weight: 11000
url: /sv/cpp/aspose.pdf/matrix3d/
---
## Matrix3D class


Klassen representerar transformationsmatris.

```cpp
class Matrix3D : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix3D\>\&) | Lägger till matris till en annan matris. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Jämför matrisen med ett annat objekt. |
| [get_A](./get_a/)() | En medlem i transformationsmatrisen. |
| [get_B](./get_b/)() | B-medlem i transformationsmatrisen. |
| [get_C](./get_c/)() | C-medlem i transformationsmatrisen. |
| [get_D](./get_d/)() | D-medlem i transformationsmatrisen. |
| [get_E](./get_e/)() | E-medlem i transformationsmatrisen. |
| [get_F](./get_f/)() | F-medlem i transformationsmatrisen. |
| [get_G](./get_g/)() | G-medlem i transformationsmatrisen. |
| [get_H](./get_h/)() | H-medlem i transformationsmatrisen. |
| [get_I](./get_i/)() | I-medlem i transformationsmatrisen. |
| [get_Tx](./get_tx/)() | Tx-medlem i transformationsmatrisen. |
| [get_Ty](./get_ty/)() | Ty-medlem i transformationsmatrisen. |
| [get_Tz](./get_tz/)() | Tz-medlem i transformationsmatrisen. |
| static [GetAngle](./getangle/)(Rotation) | Översätter rotation till vinkel (grader) |
| [GetHashCode](./gethashcode/)() const override | Hash-kod för objekt. |
| [Matrix3D](./matrix3d/)() | Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]. |
| [Matrix3D](./matrix3d/)(const System::ArrayPtr\<double\>\&) | Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F G H I Tx Ty Tz]. |
| [Matrix3D](./matrix3d/)(const System::SharedPtr\<Matrix3D\>\&) | Konstruktor accepterar en matris för att skapa en kopia. |
| [Matrix3D](./matrix3d/)(double, double, double, double, double, double, double, double, double, double, double, double) | Initierar transformationsmatris med angivna koefficienter. |
| [set_A](./set_a/)(double) | En medlem i transformationsmatrisen. |
| [set_B](./set_b/)(double) | B-medlem i transformationsmatrisen. |
| [set_C](./set_c/)(double) | C-medlem i transformationsmatrisen. |
| [set_D](./set_d/)(double) | D-medlem i transformationsmatrisen. |
| [set_E](./set_e/)(double) | E-medlem i transformationsmatrisen. |
| [set_F](./set_f/)(double) | F-medlem i transformationsmatrisen. |
| [set_G](./set_g/)(double) | G-medlem i transformationsmatrisen. |
| [set_H](./set_h/)(double) | H-medlem i transformationsmatrisen. |
| [set_I](./set_i/)(double) | I-medlem i transformationsmatrisen. |
| [set_Tx](./set_tx/)(double) | Tx-medlem i transformationsmatrisen. |
| [set_Ty](./set_ty/)(double) | Ty-medlem i transformationsmatrisen. |
| [set_Tz](./set_tz/)(double) | Tz-medlem i transformationsmatrisen. |
| [ToString](./tostring/)() const override | Returnerar textrepresentation av matrisen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
