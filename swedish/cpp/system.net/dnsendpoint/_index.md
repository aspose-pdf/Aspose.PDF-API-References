---
title: "System::Net::DnsEndPoint-klass"
linktitle: "DnsEndPoint"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::DnsEndPoint-klass. Innehåller information som används av applikationen för att ansluta till tjänsten. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.net/dnsendpoint/
---
## DnsEndPoint class


Innehåller information som används av applikationen för att ansluta till tjänsten. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DnsEndPoint : public System::Net::EndPoint
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t) | Skapar en ny instans. |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t, System::Net::Sockets::AddressFamily) | Skapar en ny instans. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_AddressFamily](./get_addressfamily/)() override | RTTI-information. |
| [get_Host](./get_host/)() | RTTI-information. |
| [get_Port](./get_port/)() | Returnerar portnumret. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
