---
title: "System::Drawing::SizeF-klass"
linktitle: "SizeF"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::SizeF-klass. Representerar ett par enkelflytande punktvärden som representerar bildens bredd och höjd. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 2300
url: /sv/cpp/system.drawing/sizef/
---
## SizeF class


Representerar ett par enkelflytande punktvärden som representerar bildens bredd och höjd. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class SizeF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(const SizeF\&, const SizeF\&) | Returnerar ett nytt [SizeF](./)-objekt som är summan av de angivna [SizeF](./)-objekten, d.v.s. vars breddvärde är lika med summan av breddvärdena för de angivna objekten och höjdvärdet är lika med summan av höjdvärdena för de angivna objekten. |
| [Equals](./equals/)(const SizeF\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av bredd- och höjdvärden. |
| [get_Height](./get_height/)() const | Returnerar höjdvärdet som representeras av det aktuella objektet. |
| [get_IsEmpty](./get_isempty/)() const | Bestämmer om både bredd- och höjdvärden är lika med 0. |
| [get_Width](./get_width/)() const | Returnerar värdet av bredden som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [operator PointF](./operatorpointf/)() const | Konverterar det aktuella objektet till en instans av [Point](../point/)-objekt genom att initiera dess X- och Y-koordinat med det aktuella objektets bredd- och höjdvärden respektive. |
| [operator+=](./operator+=/)(const SizeF\&) | Lägger till det angivna [SizeF](./)-objektets bredd- och höjdvärden till bredd- och höjdvärdena för det aktuella [SizeF](./)-objektet respektivt. |
| [set_Height](./set_height/)(float) | Ställer in värdet av höjden som representeras av det aktuella objektet. |
| [set_Width](./set_width/)(float) | Ställer in värdet för bredd som representeras av det aktuella objektet. |
| [SizeF](./sizef/)() | Skapar ett nytt [SizeF](./)-objekt och initierar dess bredd- och höjdvärden med 0. |
| [SizeF](./sizef/)(const PointF\&) | Skapar ett nytt [SizeF](./)-objekt och initierar dess bredd- och höjdvärden med värdena för X- och Y-koordinaterna för den angivna punkten respektive. |
| [SizeF](./sizef/)(float, float) | Skapar ett nytt [SizeF](./)-objekt och initierar det med det angivna värdet. |
| static [Subtract](./subtract/)(const SizeF\&, const SizeF\&) | Returnerar ett nytt [SizeF](./)-objekt som är resultatet av subtraktionen av **size2** från **size1**, d.v.s. vars breddvärde är resultatet av subtraktionen av **size2's** breddvärde från **size1's** breddvärde och höjdvärdet är resultatet av subtraktionen av **size2's** höjdvärde från **size1's** höjdvärde. |
| [ToPointF](./topointf/)() const | Konverterar det aktuella objektet till en instans av [Point](../point/)-objekt genom att initiera dess X- och Y-koordinat med det aktuella objektets bredd- och höjdvärden respektive. |
| [ToSize](./tosize/)() const | Skapar ett [Size](../size/)-objekt från det aktuella [SizeF](./)-objektet genom att trunkera [SizeF](./)-objektets bredd- och höjdvärden till nästa lägre heltal. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret av bredd- och höjdvärden som representeras av det aktuella objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [SizeF](./)-klass vars bredd- och höjdvärden är 0. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
