---
title: "System::Drawing::Drawing2D::PathGradientBrush klass"
linktitle: "PathGradientBrush"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::PathGradientBrush klass. Representerar en pensel som fyller interiören av ett GraphicsPath-objekt med en gradient. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush class


Representerar en pensel som fyller interiören av ett [GraphicsPath](../graphicspath/) objekt med en gradient. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [get_Blend](./get_blend/)() const | INTE IMPLEMENTERAD. |
| [get_CenterColor](./get_centercolor/)() const | Returnerar en färg som är i mitten av den bana som fylls av det aktuella objektet. |
| [get_CenterPoint](./get_centerpoint/)() const | Hämtar mittpunkten för gradienten. |
| [get_FocusScales](./get_focusscales/)() const | Hämtar fokuspunkten för gradientens avtagande. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Returnerar ett värde som definierar en flerfärgs linjär gradient. |
| [get_Rectangle](./get_rectangle/)() | INTE IMPLEMENTERAD. |
| [get_SurroundColors](./get_surroundcolors/)() const | Returnerar färger som motsvarar punkterna i den bana som detta [PathGradientBrush](./) fyller. |
| [get_Transform](./get_transform/)() const | Returnerar en kopia av ett [Matrix](../matrix/)‑objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [get_WrapMode](./get_wrapmode/)() const | Returnerar omslagsläget. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplicerar det aktuella objektets transformmatris med den angivna matrisen. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<PointF\>\&, WrapMode) | RTTI-information. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<Point\>\&, WrapMode) | Skapar en ny instans av [PathGradientBrush](./) klass. |
| [PathGradientBrush](./pathgradientbrush/)(const SharedPtr\<GraphicsPath\>\&) | Skapar en ny instans av [PathGradientBrush](./) klass. |
| [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformmatris så att den blir en identitetsmatris. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Ställer in en blandning som specificerar faktorer och positioner för grundfärgerna för denna pensel. |
| [set_CenterColor](./set_centercolor/)(Color) | Ställer in en färg som är i mitten av den bana som fylls av det aktuella objektet. |
| [set_CenterPoint](./set_centerpoint/)(const PointF\&) | Ställer in mittpunkten för gradienten. |
| [set_FocusScales](./set_focusscales/)(const PointF\&) | Ställer in fokuspunkten för gradientens avtagande. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Ställer in ett värde som definierar en flerfärgs linjär gradient. |
| [set_SurroundColors](./set_surroundcolors/)(const ArrayPtr\<Color\>\&) | Ställer in färger som motsvarar punkterna i den bana som detta [PathGradientBrush](./) fyller. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Ställer in ett [Matrix](../matrix/)‑objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Ställer in omslagsläget. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | INTE IMPLEMENTERAD. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | INTE IMPLEMENTERAD. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
## Se även

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
