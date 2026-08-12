---
title: "System::Net::Sockets::UdpClient-klass"
linktitle: "UdpClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::UdpClient-klass. Tillhandahåller User Datagram Protocol (UDP)-nätverkstjänster. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.sockets/udpclient/
---
## UdpClient class


Tillhandahåller User Datagram Protocol (UDP)-nätverkstjänster. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class UdpClient : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() | Stänger UDP-anslutningen. |
| [Connect](./connect/)(String, int32_t) | Upprättar en anslutning till den angivna porten på den angivna värden. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Upprättar en anslutning med värden på den angivna adressen på den angivna porten. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Upprättar en anslutning till en fjärrslutpunkt. |
| [Dispose](./dispose/)() override | Frigör de hanterade och ohanterade resurser som används av [UdpClient](./). |
| [get_Client](./get_client/)() | RTTI-information. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Returnerar ett datagram som skickats av en server. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Skickar ett UDP-datagram till värden vid den fjärranslutna slutpunkten. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Skickar ett UDP-datagram till den angivna porten på den angivna fjärrvärden. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Skickar ett UDP-datagram till en fjärrvärd. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Används för att tillhandahålla den underliggande nätverkssockeln. |
| [UdpClient](./udpclient/)() | Initierar en ny instans av [UdpClient](./)-klassen. |
| [UdpClient](./udpclient/)(AddressFamily) | Initierar en ny instans av [UdpClient](./)-klassen. |
| [UdpClient](./udpclient/)(int32_t) | Initierar en ny instans av [UdpClient](./)-klassen. |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | Initierar en ny instans av [UdpClient](./)-klassen. |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | Initierar en ny instans av [UdpClient](./)-klassen. param local EP den lokala slutpunkten som du binder UDP-anslutningen till. |
| [UdpClient](./udpclient/)(String, int32_t) | Skapar en ny instans av [UdpClient](./)-klassen och ansluter till den angivna fjärrvärden på den angivna porten. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
