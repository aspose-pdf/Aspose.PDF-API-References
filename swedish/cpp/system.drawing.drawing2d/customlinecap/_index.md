---
title: "System::Drawing::Drawing2D::CustomLineCap-klass"
linktitle: "CustomLineCap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::CustomLineCap-klass. Representerar ett användardefinierat linjekap. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.drawing.drawing2d/customlinecap/
---
## CustomLineCap class


Representerar ett användardefinierat linjekap. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CustomLineCap : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Clone](./clone/)() | Returnerar en kopia av det aktuella objektet. |
| [CustomLineCap](./customlinecap/)(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) | Skapar en ny instans av klassen [CustomLineCap](./) som representerar ett användardefinierat linjekap med de angivna egenskaperna. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [get_BaseCap](./get_basecap/)() const | Returnerar baslinjekapet som detta anpassade kap skapades från. |
| [get_BaseInset](./get_baseinset/)() const | Returnerar avståndet mellan linjen och kappen. |
| [get_StrokeJoin](./get_strokejoin/)() const | Returnerar värdet [LineJoin](../linejoin/) som bestämmer hur linjerna i detta anpassade kap sammanfogas. |
| [get_WidthScale](./get_widthscale/)() const | Returnerar skalan för detta anpassade kap. |
| [GetStrokeCaps](./getstrokecaps/)(LineCap\&, LineCap\&) | Hämtar start- och slutlinjekap för det anpassade kappen som representeras av det aktuella objektet. |
| [set_BaseCap](./set_basecap/)(LineCap) | Ställer in baslinjekapvärdet för detta anpassade kap. |
| [set_BaseInset](./set_baseinset/)(float) | Ställer in avståndet mellan linjen och kappen. |
| [set_StrokeJoin](./set_strokejoin/)(LineJoin) | Ställer in värdet [LineJoin](../linejoin/) som bestämmer hur linjerna i detta anpassade kap sammanfogas. |
| [set_WidthScale](./set_widthscale/)(float) | Ställer in skalan för detta anpassade kap. |
| [SetStrokeCaps](./setstrokecaps/)(LineCap, LineCap) | Ställer in start- och slutlinjekap för det anpassade kappen som representeras av det aktuella objektet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
