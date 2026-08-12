---
title: "System::Drawing::PointF-klass"
linktitle: "PointF"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::PointF-klass. Representerar ett par av enkelprecisions flyttal X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 1800
url: /sv/cpp/system.drawing/pointf/
---
## PointF class


Representerar ett par av enkelprecisions flyttal X- och Y-koordinater för en punkt på ett tvådimensionellt plan. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
class PointF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(const PointF\&, const SizeF\&) | Lägger till bredd- och höjdvärden från det angivna [SizeF](../sizef/)-objektet till X- och Y-koordinatvärdena i det angivna [PointF](./)-objektet respektive. |
| static [Add](./add/)(const PointF\&, const Size\&) | Lägger till bredd- och höjdvärden från det angivna [Size](../size/)-objektet till X- och Y-koordinatvärdena i det angivna [PointF](./)-objektet respektive. |
| [Equals](./equals/)(const PointF\&) const | Avgör om det aktuella objektet och det angivna objektet är lika, d.v.s. representerar samma par av X- och Y-koordinatvärden. |
| [get_IsEmpty](./get_isempty/)() const | Bestämmer om både X- och Y-koordinatvärdena är lika med 0. |
| [get_X](./get_x/)() const | Returnerar värdet för X-koordinaten som representeras av det aktuella objektet. |
| [get_Y](./get_y/)() const | Returnerar värdet för Y-koordinaten som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| explicit [operator bool](./operatorbool/)() | Returnerar alltid true. |
| [PointF](./pointf/)() | Skapar ett nytt [PointF](./)-objekt och initierar dess X- och Y-koordinatvärden till 0. |
| [PointF](./pointf/)(float, float) | Skapar ett nytt [PointF](./)-objekt och initierar det med de angivna värdena. |
| [PointF](./pointf/)(const SizeF\&) | Skapar ett nytt [PointF](./)-objekt och initierar dess X- och Y-koordinatvärden med bredd- och höjdvärden från det angivna [SizeF](../sizef/)-objektet respektive. |
| [set_X](./set_x/)(float) | Sätter värdet för X-koordinaten som representeras av det aktuella objektet. |
| [set_Y](./set_y/)(float) | Sätter värdet för Y-koordinaten som representeras av det aktuella objektet. |
| static [Subtract](./subtract/)(const PointF\&, const SizeF\&) | Subtraherar bredd- och höjdvärden från det angivna [SizeF](../sizef/)-objektet från X- och Y-koordinatvärdena i det angivna [PointF](./)-objektet respektive. |
| static [Subtract](./subtract/)(const PointF\&, const Size\&) | Subtraherar bredd- och höjdvärden från det angivna [Size](../size/)-objektet från X- och Y-koordinatvärdena i det angivna [PointF](./)-objektet respektive. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av paret X- och Y-koordinatvärden som representeras av det aktuella objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom instans av klassen [PointF](./) vars X- och Y-koordinatvärden är 0. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
