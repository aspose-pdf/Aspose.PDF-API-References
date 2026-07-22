---
title: "System::Net::Http::Headers::StringWithQualityHeaderValue klass"
linktitle: "StringWithQualityHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::StringWithQualityHeaderValue klass. Representerar ett värde med en extra kvalitet för ett stränghuvud. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2300
url: /sv/cpp/system.net.http.headers/stringwithqualityheadervalue/
---
## StringWithQualityHeaderValue class


Representerar ett värde med en extra kvalitet för ett stränghuvud. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StringWithQualityHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Quality](./get_quality/)() | Returnerar en kvalitet. |
| [get_Value](./get_value/)() | RTTI-information. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetStringWithQualityLength](./getstringwithqualitylength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [StringWithQualityHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [StringWithQualityHeaderValue](./). |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String) | Skapar en ny instans. |
| [StringWithQualityHeaderValue](./stringwithqualityheadervalue/)(String, double) | Skapar en ny instans. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<StringWithQualityHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [StringWithQualityHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
