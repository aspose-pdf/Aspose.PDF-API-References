---
title: "System::Index-klass"
linktitle: "Index"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Index-klass. Representerar ett index i en samling. Indexet kan vara från början eller från slutet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 4100
url: /sv/cpp/system/index/
---
## Index class


Representerar ett index i en samling. Indexet kan vara från början eller från slutet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(const Index\&) const | Bestämmer om den aktuella instansen och den angivna [Index](./) representerar samma position. |
| static [FromEnd](./fromend/)(int32_t) | Skapar ett [Index](./) som är relativt slutet av samlingen. |
| static [get_End](./get_end/)() | Hämtar ett [Index](./)-objekt som representerar slutet av en samling. |
| [get_IsFromEnd](./get_isfromend/)() const | Hämtar ett värde som indikerar om indexet är från slutet. |
| static [get_Start](./get_start/)() | Hämtar ett [Index](./)-objekt som representerar början av en samling. |
| [get_Value](./get_value/)() const | Hämtar indexvärdet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella indexet. |
| [GetOffset](./getoffset/)(int32_t) const | Konverterar det aktuella [Index](./) till ett avstånd från början av en samling med den angivna längden. |
| [Index](./index/)() | Skapar en instans som representerar början av en samling. |
| [Index](./index/)(int32_t) | Skapar en instans som representerar den angivna positionen från början av en samling. |
| [Index](./index/)(int32_t, bool) | Skapar en instans som representerar det angivna indexet. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
