---
title: "System::Drawing::Drawing2D::Matrix class"
linktitle: "Matrix"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::Matrix class. Representerar en 3x3-matris som definierar transformationsoperationer. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.drawing.drawing2d/matrix/
---
## Matrix class


Representerar en 3x3-matris som definierar transformationsoperationer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Matrix : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() const | Skapar en kopia av det aktuella objektet. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [Equals](./equals/)(ptr) override | Testar om det angivna objektet är en [Matrix](./) och är identiskt med detta objekt. |
| [get_Elements](./get_elements/)() const | Returnerar en array som innehåller matrisens element i följande ordning: m11, m12, m21, m22, dx, dy. |
| [get_IsIdentity](./get_isidentity/)() const | Bestämmer om matrisen som representeras av det aktuella objektet är en identitetsmatris. |
| [get_IsInvertible](./get_isinvertible/)() const | Bestämmer om matrisen som representeras av det aktuella objektet är inverterbar. |
| [get_OffsetX](./get_offsetx/)() const | Returnerar X-översättningsvärdet för matrisen som representeras av det aktuella objektet. |
| [get_OffsetY](./get_offsety/)() const | Returnerar Y-översättningsvärdet för matrisen som representeras av det aktuella objektet. |
| [Invert](./invert/)() | Inverterar matrisen som representeras av det aktuella objektet. |
| [Matrix](./matrix/)() | Skapar en ny instans av klassen [Matrix](./) som representerar en identitetsmatris. |
| [Matrix](./matrix/)(float, float, float, float, float, float) | Skapar en ny instans av klassen [Matrix](./) och initierar den med de angivna värdena. |
| [Matrix](./matrix/)(const Rectangle\&, const ArrayPtr\<Point\>\&) | Skapar en ny instans av klassen [Matrix](./) för den geometriska transformation som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix](./matrix/)(const RectangleF\&, const ArrayPtr\<PointF\>\&) | Skapar en ny instans av klassen [Matrix](./) för den geometriska transformation som definieras av den angivna rektangeln och punktarrayen. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&) | Multiplicerar matrisen som representeras av det aktuella objektet med den angivna matrisen. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplicerar matrisen som representeras av det aktuella objektet med den angivna matrisen. |
| [Reset](./reset/)() | Återställer matrisen som representeras av det aktuella objektet så att den blir en identitetsmatris. |
| [Rotate](./rotate/)(float) | Rotera matrisen som representeras av det aktuella objektet medurs med den angivna vinkeln. |
| [Rotate](./rotate/)(float, MatrixOrder) | Rotera matrisen som representeras av det aktuella objektet medurs kring origo med den angivna vinkeln. |
| [RotateAt](./rotateat/)(float, const PointF\&) | Rotera matrisen som representeras av det aktuella objektet medurs kring den angivna punkten med den angivna vinkeln. |
| [RotateAt](./rotateat/)(float, const PointF\&, MatrixOrder) | Rotera matrisen som representeras av det aktuella objektet medurs kring den angivna punkten med den angivna vinkeln. |
| [Scale](./scale/)(float, float) | Applicerar den angivna skalningsvektorn på matrisen som representeras av det aktuella objektet. |
| [Scale](./scale/)(float, float, MatrixOrder) | Applicerar den angivna skalningsvektorn på matrisen som representeras av det aktuella objektet. |
| [Shear](./shear/)(float, float) | Applicerar den angivna skevningsvektorn på matrisen som representeras av det aktuella objektet. |
| [Shear](./shear/)(float, float, MatrixOrder) | Applicerar den angivna skevningsvektorn på matrisen som representeras av det aktuella objektet. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<Point\>\&) | Applicerar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<Point\>\&) | Applicerar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<PointF\>\&) | Applicerar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<PointF\>\&) | Applicerar den geometriska transformationen som definieras av matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<Point\>\&) | Applicerar endast skalnings- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<Point\>\&) | Applicerar endast skalnings- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<PointF\>\&) | Applicerar endast skalnings- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<PointF\>\&) | Applicerar endast skalnings- och roteringskomponenterna i matrisen som representeras av det aktuella objektet på de angivna punkterna. |
| [Translate](./translate/)(float, float) | Applicerar den angivna translationsvektorn på matrisen som representeras av det aktuella objektet. |
| [Translate](./translate/)(float, float, MatrixOrder) | Applicerar den angivna translationsvektorn på matrisen som representeras av det aktuella objektet. |
| [VectorTransformPoints](./vectortransformpoints/)(const ArrayPtr\<Point\>\&) | Multiplicerar varje vektor i en array med matrisen som representeras av det aktuella objektet. |
| [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<Point\>\&) | Multiplicerar varje vektor i en array med matrisen som representeras av det aktuella objektet. |
| virtual [~Matrix](./~matrix/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
