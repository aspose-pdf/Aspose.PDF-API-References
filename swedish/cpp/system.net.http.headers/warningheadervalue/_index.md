---
title: "System::Net::Http::Headers::WarningHeaderValue-klass"
linktitle: "WarningHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::WarningHeaderValue-klass. Representerar ett värde av ''Warning''-headern. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2700
url: /sv/cpp/system.net.http.headers/warningheadervalue/
---
## WarningHeaderValue class


Representerar ett värde av 'Warning'-headern. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class WarningHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Agent](./get_agent/)() | Returnerar värden som är kopplad till varningen. |
| [get_Code](./get_code/)() | RTTI-information. |
| [get_Date](./get_date/)() | Returnerar datum/tid för varningen. |
| [get_Text](./get_text/)() | Returnerar varningstexten. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetWarningLength](./getwarninglength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [WarningHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [WarningHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<WarningHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [WarningHeaderValue](./). |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String) | Skapar en ny instans. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String, DateTimeOffset) | Skapar en ny instans. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
