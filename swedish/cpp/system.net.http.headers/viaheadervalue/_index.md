---
title: "System::Net::Http::Headers::ViaHeaderValue klass"
linktitle: "ViaHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::ViaHeaderValue klass. Representerar ett värde för ''Via''-huvudet. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr‑pekare och använd den pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.net.http.headers/viaheadervalue/
---
## ViaHeaderValue class


Representerar ett värde för 'Via'-huvudet. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class ViaHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Comment](./get_comment/)() | Returnerar kommentaren från 'Via'-huvudvärdet. |
| [get_ProtocolName](./get_protocolname/)() | RTTI-information. |
| [get_ProtocolVersion](./get_protocolversion/)() | Returnerar protokollversionen från 'Via'-headerns värde. |
| [get_ReceivedBy](./get_receivedby/)() | Returnerar värdnamnet och porten som begäran eller svaret mottogs av. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetViaLength](./getvialength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [ViaHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [ViaHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ViaHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [ViaHeaderValue](./). |
| [ViaHeaderValue](./viaheadervalue/)(String, String) | Skapar en ny instans. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String) | Skapar en ny instans. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String, String) | Skapar en ny instans. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
