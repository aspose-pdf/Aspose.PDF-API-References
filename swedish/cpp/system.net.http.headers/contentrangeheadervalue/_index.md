---
title: "System::Net::Http::Headers::ContentRangeHeaderValue class"
linktitle: "ContentRangeHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::ContentRangeHeaderValue-klass. Representerar ett värde för ''Content-Range''-huvudet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue class


Representerar ett värde för 'Content-Range'-huvudet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t, int64_t) | Skapar en ny instans. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t) | Skapar en ny instans. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t) | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_From](./get_from/)() | Hämtar en position där datasändning måste börja. |
| [get_HasLength](./get_haslength/)() const | Hämtar ett värde som indikerar om längden är specificerad för det aktuella huvudet. |
| [get_HasRange](./get_hasrange/)() const | Hämtar ett värde som indikerar om intervallet är specificerat för det aktuella huvudet. |
| [get_Length](./get_length/)() | Hämtar längden på en entitetskropp. |
| [get_To](./get_to/)() | Hämtar en position där datasändning måste stoppas. |
| [get_Unit](./get_unit/)() | RTTI-information. |
| static [GetContentRangeLength](./getcontentrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från den specificerade positionen till en instans av klassen [ContentRangeHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [ContentRangeHeaderValue](./). |
| [set_Unit](./set_unit/)(String) | Ställer in enheter som används i intervallet. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [ContentRangeHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
