---
title: "System::Drawing::Size klass"
linktitle: "Size"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Size klass. Representerar ett par heltalsvärden som anger bildens bredd och höjd. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ i C++."
type: docs
weight: 2200
url: /sv/cpp/system.drawing/size/
---
## Size class


Representerar ett par heltalsvärden som anger bildens bredd och höjd. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Size
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(const Size\&, const Size\&) | Returnerar ett nytt [Size](./)-objekt som är summan av det angivna [Size](./)-objektet, d.v.s. vars breddvärde är lika med summan av breddvärdena för de angivna objekten och höjdvärdet är lika med summan av höjdvärdena för de angivna objekten. |
| static [Ceiling](./ceiling/)(const SizeF\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att avrunda [SizeF](../sizef/)-objektets bredd- och höjdvärden till nästa högre heltal. |
| [Equals](./equals/)(const Size\&) const | Bestämmer om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av bredd- och höjdvärden. |
| [get_Height](./get_height/)() const | Returnerar värdet av höjden som representeras av det aktuella objektet. |
| [get_IsEmpty](./get_isempty/)() const | Bestämmer om både bredd- och höjdvärden är lika med 0. |
| [get_Width](./get_width/)() const | Returnerar värdet av bredden som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [operator Point](./operatorpoint/)() const | Skapar en instans av [Point](../point/)-objektet och initierar dess X- och Y-koordinat med det aktuella objektets bredd- och höjdvärden respektive. |
| [operator SizeF](./operatorsizef/)() const | Skapar en instans av [SizeF](../sizef/)-objektet och initierar det med bredd- och höjdvärden från det aktuella [Size](./)-objektet. |
| static [Round](./round/)(const SizeF\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att avrunda [SizeF](../sizef/)-objektets bredd- och höjdvärden till närmaste heltal. |
| [set_Height](./set_height/)(int) | Ställer in värdet av höjden som representeras av det aktuella objektet. |
| [set_Width](./set_width/)(int) | Ställer in värdet för bredd som representeras av det aktuella objektet. |
| [Size](./size/)() | Skapar ett nytt [Size](./)-objekt och initierar dess bredd- och höjdvärden med 0. |
| [Size](./size/)(const Point\&) | Skapar ett nytt [Size](./)-objekt och initierar dess bredd- och höjdvärden med värdena för X- och Y-koordinaterna för den angivna punkten respektive. |
| [Size](./size/)(int, int) | Skapar ett nytt [Size](./)-objekt och initierar det med det angivna värdet. |
| static [Subtract](./subtract/)(const Size\&, const Size\&) | Returnerar ett nytt [Size](./)-objekt som är resultatet av subtraktion av **size2** från **size1**, d.v.s. vars breddvärde är resultatet av subtraktion av **size2's** breddvärde från **size1's** breddvärde och vars höjdvärde är resultatet av subtraktion av **size2's** höjdvärde från **size1's** höjdvärde. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret av bredd- och höjdvärden som representeras av det aktuella objektet. |
| static [Truncate](./truncate/)(const SizeF\&) | Skapar ett [Size](./)-objekt från det angivna [SizeF](../sizef/)-objektet genom att trunkera [SizeF](../sizef/)-objektets bredd- och höjdvärden till närmaste lägre heltalsvärden. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av [Size](./)-klassen vars bredd- och höjdvärden är 0. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
