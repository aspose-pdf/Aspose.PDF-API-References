---
title: "System::Net::Http::Headers::EntityTagHeaderValue-klass"
linktitle: "EntityTagHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::EntityTagHeaderValue-klass. Representerar ett värde för ''Entity-Tag''-huvudet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.net.http.headers/entitytagheadervalue/
---
## EntityTagHeaderValue class


Representerar ett värde för ''Entity-Tag''-huvudet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class EntityTagHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String) | Skapar en ny instans. |
| [EntityTagHeaderValue](./entitytagheadervalue/)(String, bool) | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static [get_Any](./get_any/)() | Hämtar ett värde för ''ETag''-huvudet. |
| [get_IsWeak](./get_isweak/)() | Hämtar ett värde som indikerar om den aktuella instansen är en svag validator. |
| [get_Tag](./get_tag/)() | RTTI-information. |
| static [GetEntityTagLength](./getentitytaglength/)(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [EntityTagHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [EntityTagHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<EntityTagHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [EntityTagHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
