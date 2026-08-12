---
title: "System::Drawing::Imaging::ImageAttributes-klass"
linktitle: "ImageAttributes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::ImageAttributes-klass. Representerar information om hur bildfärger manipuleras under rendering. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.drawing.imaging/imageattributes/
---
## ImageAttributes class


Representerar information om hur bildfärger manipuleras under rendering. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ImageAttributes : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ClearBrushRemapTable](./clearbrushremaptable/)() | INTE IMPLEMENTERAD. |
| [ClearColorKey](./clearcolorkey/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearColorMatrix](./clearcolormatrix/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearGamma](./cleargamma/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearNoOp](./clearnoop/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearOutputChannel](./clearoutputchannel/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearRemapTable](./clearremaptable/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ClearThreshold](./clearthreshold/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [Clone](./clone/)() | Skapar en kopia av det aktuella objektet. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [GetAdjustedPalette](./getadjustedpalette/)(const SharedPtr\<ColorPalette\>\&, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [ImageAttributes](./imageattributes/)() | Standardkonstruktor. |
| [SetBrushRemapTable](./setbrushremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&) | INTE IMPLEMENTERAD. |
| [SetColorKey](./setcolorkey/)(Color, Color, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetColorMatrices](./setcolormatrices/)(const SharedPtr\<ColorMatrix\>\&, const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetColorMatrix](./setcolormatrix/)(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen. |
| [SetGamma](./setgamma/)(float, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetNoOp](./setnoop/)(ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetOutputChannel](./setoutputchannel/)(ColorChannelFlag, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const String\&, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetRemapTable](./setremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetThreshold](./setthreshold/)(float, ColorAdjustType) | INTE IMPLEMENTERAD. |
| [SetWrapMode](./setwrapmode/)(Drawing2D::WrapMode, Color, bool) | Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
