---
title: "System::Drawing::TextureBrush-klass"
linktitle: "TextureBrush"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::TextureBrush-klass. Representerar en pensel som använder en bild för att fylla insidan av en form. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2800
url: /sv/cpp/system.drawing/texturebrush/
---
## TextureBrush class


Representerar en pensel som använder en bild för att fylla insidan av en form. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TextureBrush : public System::Drawing::Brush
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [get_Image](./get_image/)() | Returnerar en bild som används av det aktuella [TextureBrush](./)-objektet. |
| [get_Transform](./get_transform/)() | Returnerar en kopia av ett Matrix-objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [get_WrapMode](./get_wrapmode/)() | Returnerar ett värde som anger hur penseln som representeras av det aktuella objektet upprepas. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplicerar det aktuella objektets transformmatris med den angivna matrisen. |
| [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformmatris så att den blir en identitetsmatris. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [set_Transform](./set_transform/)(const System::SharedPtr\<Drawing2D::Matrix\>\&) | Ställer in ett Matrix-objekt som specificerar de geometriska transformationerna för penseln som representeras av det aktuella objektet. |
| [set_WrapMode](./set_wrapmode/)(Drawing2D::WrapMode) | Ställer in ett värde som anger hur penseln som representeras av det aktuella objektet upprepas. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) | Skapar en ny instans av [TextureBrush](./)-klassen som använder den angivna bilden. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) | Skapar en ny instans av [TextureBrush](./)-klassen som använder den angivna bilden. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) | Skapar en ny instans av [TextureBrush](./)-klassen som använder den angivna bilden. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) | Skapar en ny instans av [TextureBrush](./)-klassen som använder den angivna bilden. |
| [TextureBrush](./texturebrush/)(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) | Skapar en ny instans av [TextureBrush](./)-klassen som använder den angivna bilden. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| virtual [~TextureBrush](./~texturebrush/)() | Destruktor. |
## Se även

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
