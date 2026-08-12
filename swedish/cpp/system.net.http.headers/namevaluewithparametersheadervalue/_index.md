---
title: "System::Net::Http::Headers::NameValueWithParametersHeaderValue-klass"
linktitle: "NameValueWithParametersHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::NameValueWithParametersHeaderValue-klass. Representerar ett nyckel/värde-par med parametrar för användning i headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Representerar ett nyckel/värde-par med parametrar för användning i rubriker. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Parameters](./get_parameters/)() | RTTI-information. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueWithParametersHeaderValue](./). |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String) | Skapar en ny instans. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String, String) | Skapar en ny instans. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Skapar en ny instans. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [NameValueWithParametersHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [NameValueWithParametersHeaderValue](./). |
## Se även

* Class [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
