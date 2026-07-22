---
title: "System::Drawing::Point-klass"
linktitle: "Point"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Point-klass. Representerar ett par heltals‑X‑ och Y‑koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig System::SmartPtr‑klass för att hantera objekt av denna typ i C++."
type: docs
weight: 1700
url: /sv/cpp/system.drawing/point/
---
## Point class


Representerar ett par heltals‑X‑ och Y‑koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../../system/smartptr/)‑klass för att hantera objekt av denna typ.

```cpp
class Point
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(const Point\&, const Size\&) | Lägger till bredd‑ och höjdvärden för det specificerade [Size](../size/)‑objektet till X‑ och Y‑koordinatvärdena för det specificerade [Point](./)‑objektet på motsvarande sätt. |
| static [Ceiling](./ceiling/)(const PointF\&) | Skapar ett [Point](./)‑objekt från det specificerade [PointF](../pointf/)‑objektet genom att avrunda [PointF](../pointf/)‑objektets X‑ och Y‑koordinatvärden till nästa högre heltalsvärde. |
| [Equals](./equals/)(const Point\&) const | Avgör om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av X- och Y-koordinatvärden. |
| [get_IsEmpty](./get_isempty/)() const | Bestämmer om både X- och Y-koordinatvärdena är lika med 0. |
| [get_X](./get_x/)() const | Returnerar värdet för X-koordinaten som representeras av det aktuella objektet. |
| [get_Y](./get_y/)() const | Returnerar värdet för Y-koordinaten som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [getStdHash](./getstdhash/)() const | Returnerar ett hash‑värde för det aktuella objektet. |
| [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| [Offset](./offset/)(int, int) | Förskjuter X‑ och Y‑koordinatvärdet som representeras av det aktuella objektet med de specificerade värdena. |
| [Offset](./offset/)(Point) | Förskjuter X‑ och Y‑koordinaterna som representeras av det aktuella objektet med värdena för X‑ och Y‑koordinaterna som representeras av det specificerade [Point](./)‑objektet på motsvarande sätt. |
| [operator PointF](./operatorpointf/)() const | Skapar en instans av [PointF](../pointf/)‑objektet och initierar det med X‑ och Y‑koordinatvärdena från det aktuella [Point](./)‑objektet. |
| [operator Size](./operatorsize/)() const | Skapar en instans av [Size](../size/)‑objektet och initierar dess bredd‑ och höjdvärden med X‑ och Y‑koordinatvärdena som representeras av det aktuella objektet på motsvarande sätt. |
| [Point](./point/)() | Skapar ett nytt [Point](./)‑objekt och initierar dess X‑ och Y‑koordinatvärden med 0. |
| [Point](./point/)(int, int) | Skapar ett nytt [Point](./)-objekt och initierar det med de angivna värdena. |
| [Point](./point/)(const Size\&) | Skapar ett nytt [Point](./)-objekt och initierar dess X- och Y-koordinatvärden med bredd- och höjdvärden från det specificerade [SizeF](../sizef/)-objektet respektive. |
| [Point](./point/)(int) | Skapar ett nytt [Point](./)-objekt och initierar dess X-koordinatvärde med ett värde bildat av de högsta 16 bitarna i det specificerade 32‑bitars heltalet och dess Y-koordinatvärde med ett värde bildat av de lägsta 16 bitarna i det specificerade 32‑bitars heltalet. |
| static [Round](./round/)(const PointF\&) | Skapar ett [Point](./)-objekt från det specificerade [PointF](../pointf/)-objektet genom att avrunda [PointF](../pointf/)-objektets X- och Y-koordinatvärden till närmaste heltal. |
| [set_X](./set_x/)(int) | Sätter värdet för X-koordinaten som representeras av det aktuella objektet. |
| [set_Y](./set_y/)(int) | Sätter värdet för Y-koordinaten som representeras av det aktuella objektet. |
| static [Subtract](./subtract/)(const Point\&, const Size\&) | Subtraherar bredd- och höjdvärden från det specificerade [Size](../size/)-objektet från X- och Y-koordinatvärdena i det specificerade [Point](./)-objektet respektive. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret X- och Y-koordinatvärden som representeras av det aktuella objektet. |
| static [Truncate](./truncate/)(const PointF\&) | Skapar ett [Point](./)-objekt från det specificerade [PointF](../pointf/)-objektet genom att trunkera [PointF](../pointf/)-objektets X- och Y-koordinatvärden till nästa lägre heltal. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av klassen [Point](./) vars X- och Y-koordinatvärden är 0. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
