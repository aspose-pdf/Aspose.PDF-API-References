---
title: "System::Net::Http::Headers::ProductHeaderValue klass"
linktitle: "ProductHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::ProductHeaderValue klass. Representerar en produkttoken i ett värde av ''User-Agent''-headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1700
url: /sv/cpp/system.net.http.headers/productheadervalue/
---
## ProductHeaderValue class


Representerar en produkttoken i ett värde av 'User-Agent'-headern. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ProductHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Name](./get_name/)() | RTTI-information. |
| [get_Version](./get_version/)() | Returnerar produkttoken‑versionen. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetProductLength](./getproductlength/)(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [ProductHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [ProductHeaderValue](./). |
| [ProductHeaderValue](./productheadervalue/)(String) | Skapar en ny instans. |
| [ProductHeaderValue](./productheadervalue/)(String, String) | Skapar en ny instans. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ProductHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [ProductHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
