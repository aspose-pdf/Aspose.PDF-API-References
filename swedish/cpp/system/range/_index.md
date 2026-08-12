---
title: "System::Range-klass"
linktitle: "Range"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Range-klass. Representerar ett intervall med ett start- och slutindex. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 5500
url: /sv/cpp/system/range/
---
## Range class


Representerar ett intervall med ett start- och slutindex. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klassen för att hantera objekt av denna typ.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [EndAt](./endat/)(const Index\&) | Skapar ett intervall som börjar vid början av samlingen och slutar vid det angivna slutindexet. |
| [Equals](./equals/)(const Range\&) const | Bestämmer om det aktuella intervallet är lika med det angivna intervallet. |
| static [get_All](./get_all/)() | Returnerar en [Range](./) som representerar hela samlingen. |
| [get_End](./get_end/)() const | Hämtar slutindexet. |
| [get_Start](./get_start/)() const | Hämtar startindexet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella intervallet. |
| [GetOffsetAndLength](./getoffsetandlength/)(int32_t) const | Beräknar den nollbaserade startoffseten och längden för den angivna samlingslängden. |
| [Range](./range/)() | Skapar ett tomt intervall. |
| [Range](./range/)(const Index\&, const Index\&) | Skapar ett [Range](./) från de angivna start- och slutindexen. |
| static [StartAt](./startat/)(const Index\&) | Skapar ett intervall som börjar vid det angivna startindexet och sträcker sig till slutet av samlingen. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
