---
title: "System::Drawing::Drawing2D::LinearGradientBrush klass"
linktitle: "LinearGradientBrush"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::LinearGradientBrush-klass. Representerar en linjär gradientpensel. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush class


Representerar en linjär gradientpensel. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [get_Blend](./get_blend/)() const | Returnerar en blandning som specificerar faktorer och positioner för grundfärgerna för denna pensel. |
| [get_GammaCorrection](./get_gammacorrection/)() const | Returnerar ett värde som indikerar att gammakorrigering är aktiverad för denna pensel. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Returnerar ett [ColorBlend](../colorblend/)‑objekt som definierar ett flerfärgslinjärt gradient. |
| [get_LinearColors](./get_linearcolors/)() const | Returnerar start- och slutfärger för denna gradient. |
| [get_Rectangle](./get_rectangle/)() | Returnerar en omgivande rektangel. |
| [get_Transform](./get_transform/)() const | Returnerar en kopia av ett [Matrix](../matrix/)‑objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [get_WrapMode](./get_wrapmode/)() const | Returnerar omslagsläget. |
| [LinearGradientBrush](./lineargradientbrush/)(const PointF\&, const PointF\&, const Color\&, const Color\&) | RTTI-information. |
| [LinearGradientBrush](./lineargradientbrush/)(const Point\&, const Point\&, const Color\&, const Color\&) | Skapar en ny instans av [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, LinearGradientMode) | Skapar en ny instans av [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, LinearGradientMode) | Skapar en ny instans av [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, float, bool) | Skapar en ny instans av [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, float, bool) | Skapar en ny instans av [LinearGradientBrush](./). |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplicerar det aktuella objektets transformmatris med den angivna matrisen. |
| [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformationsmatris. |
| [RotateTransform](./rotatetransform/)(float, MatrixOrder) | Roterar det aktuella objektets transformationsmatris. |
| [ScaleTransform](./scaletransform/)(float, float, MatrixOrder) | Skalar det aktuella objektets transformationsmatris. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Ställer in en blandning som specificerar faktorer och positioner för grundfärgerna för denna pensel. |
| [set_GammaCorrection](./set_gammacorrection/)(bool) | Ställer in gammakorrigeringsstatus för denna pensel. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Ställer in ett [ColorBlend](../colorblend/)‑objekt som definierar ett flerfärgslinjärt gradient. |
| [set_LinearColors](./set_linearcolors/)(const ArrayPtr\<Color\>\&) | Ställer in start- och slutfärger för denna gradient. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Ställer in ett [Matrix](../matrix/)‑objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Ställer in omslagsläget. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | INTE IMPLEMENTERAD. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | INTE IMPLEMENTERAD. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Översätter det aktuella objektets transformmatris. |
## Se även

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
