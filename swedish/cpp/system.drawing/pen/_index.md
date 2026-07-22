---
title: "System::Drawing::Pen class"
linktitle: "Pen"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Pen class. Representerar egenskaper såsom färg, bredd osv. för de linjer och kurvor som ritas. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.drawing/pen/
---
## Pen class


Representerar egenskaper såsom färg, bredd osv. för de linjer och kurvor som ritas. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Pen : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Returnerar en kopia av det aktuella objektet. |
| [Dispose](./dispose/)() | Frigör alla operativa resurser som erhållits av det aktuella objektet. |
| [get_Alignment](./get_alignment/)() const | Returnerar ett värde som indikerar justeringen av det aktuella [Pen](./)-objektet. |
| [get_Brush](./get_brush/)() | Returnerar denna pennas [Brush](../brush/)-objekt. |
| [get_Color](./get_color/)() const | Returnerar denna pennas färg. |
| [get_CompoundArray](./get_compoundarray/)() const | Returnerar en array av värden som specificerar en sammansatt penna. |
| [get_DashCap](./get_dashcap/)() const | Returnerar ett värde som indikerar den cap som används i båda ändarna av en streckad linje. |
| [get_DashOffset](./get_dashoffset/)() const | Returnerar avståndet från början av en linje till starten av ett streckmönster. |
| [get_DashPattern](./get_dashpattern/)() const | Returnerar en array som anger ett anpassat streckmönster i en streckad linje. |
| [get_DashStyle](./get_dashstyle/)() const | Returnerar ett värde som indikerar streckstilen för det aktuella [Pen](./)-objektet. |
| [get_EndCap](./get_endcap/)() const | Returnerar ett värde som indikerar den avslutande linjekappen för det aktuella [Pen](./)-objektet. |
| [get_LineJoin](./get_linejoin/)() const | Returnerar ett värde som indikerar hur linjerna som ritas av detta [Pen](./)-objekt förenas. |
| [get_MiterLimit](./get_miterlimit/)() const | Returnerar gränsen för tjockleken på föreningen i ett fasat hörn. |
| [get_PenType](./get_pentype/)() const | INTE IMPLEMENTERAD. |
| [get_StartCap](./get_startcap/)() const | Returnerar ett värde som indikerar den inledande linjekappen för det aktuella [Pen](./)-objektet. |
| [get_Transform](./get_transform/)() | Returnerar en kopia av ett Matrix-objekt som specificerar de geometriska transformationerna för pennan som representeras av det aktuella objektet. |
| [get_Width](./get_width/)() const | Returnerar bredden på det aktuella [Pen](./)-objektet. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplicerar det aktuella objektets transformmatris med den angivna matrisen. |
| [Pen](./pen/)(const Color\&) | Skapar ett nytt [Pen](./)-objekt som representerar den angivna färgen. |
| [Pen](./pen/)(const Color\&, float) | Skapar ett nytt [Pen](./)-objekt som representerar den angivna färgen och bredden. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&) | Skapar ett nytt [Pen](./)-objekt och initierar det med det angivna [Brush](../brush/)-objektet. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&, float) | Skapar ett nytt [Pen](./)-objekt och initierar det med det angivna [Brush](../brush/)-objektet. |
| [ResetTransform](./resettransform/)() | Återställer det aktuella objektets transformmatris så att den blir en identitetsmatris. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [set_Alignment](./set_alignment/)(Drawing2D::PenAlignment) | Ställer in justeringen av det aktuella [Pen](./)-objektet. |
| [set_Brush](./set_brush/)(const SharedPtr\<Brush\>\&) | Ställer in denna pennas [Brush](../brush/)-objekt. |
| [set_Color](./set_color/)(const Color\&) | Ställer in denna pennas färg. |
| [set_CompoundArray](./set_compoundarray/)(const System::ArrayPtr\<float\>\&) | Ställer in en array av värden som specificerar en sammansatt penna. |
| [set_CustomEndCap](./set_customendcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Ställer in den anpassade avslutande linjekappen. |
| [set_CustomStartCap](./set_customstartcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Ställer in den anpassade inledande linjekappen. |
| [set_DashCap](./set_dashcap/)(Drawing2D::DashCap) | Ställer in ett värde som specificerar den cap som används i båda ändarna av en streckad linje. |
| [set_DashOffset](./set_dashoffset/)(float) | Ställer in avståndet från början av en linje till starten av ett streckmönster. |
| [set_DashPattern](./set_dashpattern/)(const System::ArrayPtr\<float\>\&) | Ställer in en array som specificerar ett anpassat streckmönster i en streckad linje. Arrayen består av tal som anger längden på alternerande streck och mellanslag. |
| [set_DashStyle](./set_dashstyle/)(Drawing2D::DashStyle) | Ställer in ett värde som specificerar streckstilen för det aktuella [Pen](./)-objektet. |
| [set_EndCap](./set_endcap/)(Drawing2D::LineCap) | Ställer in slutlinjens ändkappa för det aktuella [Pen](./)-objektet. |
| [set_LineJoin](./set_linejoin/)(Drawing2D::LineJoin) | Ställer in ett värde som specificerar hur linjerna som ritas av detta [Pen](./)-objekt sammanfogas. |
| [set_MiterLimit](./set_miterlimit/)(float) | Ställer in gränsen för tjockleken på fogen i ett snedställt hörn. |
| [set_StartCap](./set_startcap/)(Drawing2D::LineCap) | Ställer in startlinjens ändkappa för det aktuella [Pen](./)-objektet. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Ställer in ett Matrix-objekt som specificerar de geometriska transformationerna för pennan som representeras av det aktuella objektet. |
| [set_Width](./set_width/)(float) | Ställer in bredden på det aktuella [Pen](./)-objektet. |
| [SetLineCap](./setlinecap/)(Drawing2D::LineCap, Drawing2D::LineCap, Drawing2D::DashCap) | INTE IMPLEMENTERAD. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
