---
title: "System::Net::Sockets::IPPacketInformation klass"
linktitle: "IPPacketInformation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::IPPacketInformation-klass. Representerar information om paketet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.net.sockets/ippacketinformation/
---
## IPPacketInformation class


Representerar information om paketet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IPPacketInformation : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför två objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| [get_Address](./get_address/)() | Returnerar adressen från vilken paketet tas emot. |
| [get_Interface](./get_interface/)() | Returnerar information om nätverksgränssnittet. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [IPPacketInformation](./ippacketinformation/)(System::SharedPtr\<IPAddress\>, int32_t) | Skapar en ny instans. |
| [IPPacketInformation](./ippacketinformation/)() | Skapar en ny instans. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
