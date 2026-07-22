---
title: "System::Net::SocketAddress klass"
linktitle: "SocketAddress"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::SocketAddress klass. Används för att lagra serialiserad information om EndPoint-klassinstanser. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3300
url: /sv/cpp/system.net/socketaddress/
---
## SocketAddress class


Används för att lagra serialiserad information om [EndPoint](../endpoint/)-klassinstanser. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SocketAddress : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Family](./get_family/)() | RTTI-information. |
| [get_Size](./get_size/)() | Returnerar den underliggande buffertens storlek. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [idx_get](./idx_get/)(int32_t) | Hämtar ett värde från den underliggande bufferten på det angivna indexet. |
| [idx_set](./idx_set/)(int32_t, uint8_t) | Sätter ett värde i den underliggande bufferten på det angivna indexet. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily) | Skapar en ny instans. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily, int32_t) | Skapar en ny instans. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
