---
title: "System::Net::IPAddress-klass"
linktitle: "IPAddress"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::IPAddress-klass. Representerar IP-adressen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.net/ipaddress/
---
## IPAddress class


Representerar IP-adressen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IPAddress : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_AddressFamily](./get_addressfamily/)() | Returnerar adressfamiljen. |
| [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Returnerar ett värde som indikerar om adressen är en IPv4-adress och är mappad till en IPv6-adress. |
| [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Returnerar ett värde som indikerar om adressen är en IPv6 link‑local‑adress. |
| [get_IsIPv6Multicast](./get_isipv6multicast/)() | Returnerar ett värde som indikerar om adressen är en global IPv6 multicast‑adress. |
| [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Returnerar ett värde som indikerar om adressen är en IPv6 site‑local‑adress. |
| [get_IsIPv6Teredo](./get_isipv6teredo/)() | Returnerar ett värde som indikerar om adressen är en IPv6 Teredo‑adress. |
| [get_ScopeId](./get_scopeid/)() | Hämtar omfångsidentifieraren för IPv6-adressen. |
| [GetAddressBytes](./getaddressbytes/)() | Returnerar en bytearray för IP-adressen. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [GetImpl](./getimpl/)() const | Returnerar en pekare till implementationen. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int64_t) | Konverterar den specificerade värdadressens byteordning till motsvarande nätverksbyteordning. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int32_t) | Konverterar den specificerade värdadressens byteordning till motsvarande nätverksbyteordning. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int16_t) | Konverterar den specificerade värdadressens byteordning till motsvarande nätverksbyteordning. |
| [IPAddress](./ipaddress/)(int64_t) | Skapar en ny instans. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>, int64_t) | Skapar en ny instans. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>) | Skapar en ny instans. |
| [IPAddress](./ipaddress/)() | Skapar en ny instans. |
| static [IsLoopback](./isloopback/)(System::SharedPtr\<IPAddress\>) | Returnerar ett värde som indikerar om den specificerade adressen är en loopback‑adress. |
| [MapToIPv4](./maptoipv4/)() | Mappar adressen till IPv4-adressen. |
| [MapToIPv6](./maptoipv6/)() | Mappar adressen till IPv6-adressen. |
| static [NetworkToHostOrder](./networktohostorder/)(int64_t) | Konverterar den specificerade nätverksbyteordningen till motsvarande värdadressens byteordning. |
| static [NetworkToHostOrder](./networktohostorder/)(int32_t) | Konverterar den specificerade nätverksbyteordningen till motsvarande värdadressens byteordning. |
| static [NetworkToHostOrder](./networktohostorder/)(int16_t) | Konverterar den specificerade nätverksbyteordningen till motsvarande värdadressens byteordning. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [IPAddress](./). |
| [set_ScopeId](./set_scopeid/)(int64_t) | Ställer in omfångsidentifieraren för IPv6-adressen. |
| [SetImpl](./setimpl/)(ImplPtr) | Ställer in en pekare till implementationen. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<IPAddress\>\&) | Försöker konvertera en given sträng till en instans av klassen [IPAddress](./). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Any](./any/) | RTTI-information. |
| static [Broadcast](./broadcast/) | IPv4-broadcastadressen. |
| static [IPv6Any](./ipv6any/) | IPv6-adressen som indikerar om servern måste lyssna på alla nätverksgränssnitt. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6-loopbackadressen. |
| static [IPv6None](./ipv6none/) | IPv6-adressen som indikerar om servern inte får lyssna på något nätverksgränssnitt. |
| static [Loopback](./loopback/) | IPv4-loopbackadressen. |
| static [None](./none/) | IPv4-adressen som indikerar om servern inte får lyssna på något nätverksgränssnitt. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ImplPtr](./implptr/) | En pekare till implementationstypen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
