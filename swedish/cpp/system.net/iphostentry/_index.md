---
title: "System::Net::IPHostEntry-klass"
linktitle: "IPHostEntry"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::IPHostEntry-klass. Representerar information om en internetvärdadress. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.net/iphostentry/
---
## IPHostEntry class


Representerar information om en internetvärdadress. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IPHostEntry : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AddressList](./get_addresslist/)() | Hämtar samlingen av IP-adresser för värden. |
| [get_Aliases](./get_aliases/)() | Hämtar samlingen av alias för värden. |
| [get_HostName](./get_hostname/)() const | RTTI-information. |
| [IPHostEntry](./iphostentry/)() | Skapar en ny instans. |
| [set_AddressList](./set_addresslist/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>) | Ställer in en samling av IP-adresser för värden. |
| [set_Aliases](./set_aliases/)(System::ArrayPtr\<String\>) | Ställer in en samling av alias för värden. |
| [set_HostName](./set_hostname/)(String) | Ställer in värdens namn. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
