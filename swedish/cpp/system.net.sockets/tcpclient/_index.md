---
title: "System::Net::Sockets::TcpClient-klass"
linktitle: "TcpClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::TcpClient-klass. Representerar en klient för TCP-nätverkstjänsterna. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.net.sockets/tcpclient/
---
## TcpClient class


Representerar en klient för TCP-nätverkstjänsterna. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TcpClient : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron anslutningsoperation. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron anslutningsoperation. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron anslutningsoperation. |
| [Close](./close/)() | Stänger anslutningen och frigör den aktuella instansen. |
| [Connect](./connect/)(String, int32_t) | Upprättar en anslutning till den angivna fjärrvärden. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Upprättar en anslutning till den angivna fjärrvärden. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Upprättar en anslutning till den angivna fjärrvärden. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Upprättar en anslutning till den angivna fjärrvärden. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona anslutningsoperationen är klar. |
| [get_Available](./get_available/)() | Returnerar antalet byte som har mottagits och är klara att läsas. |
| [get_Client](./get_client/)() | RTTI-information. |
| [get_Connected](./get_connected/)() | Returnerar ett värde som indikerar om socketen är ansluten till fjärrvärden. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Hämtar ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| [get_LingerState](./get_lingerstate/)() | Hämtar ett värde som indikerar om socketen kommer att fördröja stängning i ett försök att skicka all väntande data. |
| [get_NoDelay](./get_nodelay/)() | Hämtar ett värde som indikerar om den aktuella instansen använder Nagle-algoritmen. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Hämtar storleken på bufferten som används för att ta emot data. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Hämtar ett värde som anger en tidsmängd efter vilken mottagning av data får timeout. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Hämtar storleken på bufferten som används för att skicka data. |
| [get_SendTimeout](./get_sendtimeout/)() | Hämtar ett värde som anger en tidsmängd efter vilken sändning av data får timeout. |
| [GetStream](./getstream/)() | Returnerar strömmen som används för att skicka och ta emot data. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Ställer in socketen. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Ställer in ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Ställer in ett värde som indikerar om socketen kommer att fördröja stängning i ett försök att skicka all väntande data. |
| [set_NoDelay](./set_nodelay/)(bool) | Ställer in ett värde som indikerar om den aktuella instansen använder Nagle-algoritmen. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Ställer in storleken på bufferten som används för att ta emot data. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Ställer in ett värde som anger en tidsmängd efter vilken mottagning av data får timeout. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Ställer in storleken på bufferten som används för att skicka data. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Ställer in ett värde som anger en tidsmängd efter vilken sändning av data får timeout. |
| [TcpClient](./tcpclient/)(System::SharedPtr\<IPEndPoint\>) | Skapar en ny instans. |
| [TcpClient](./tcpclient/)() | Skapar en ny instans. |
| [TcpClient](./tcpclient/)(AddressFamily) | Skapar en ny instans. |
| [TcpClient](./tcpclient/)(String, int32_t) | Skapar en ny instans. |
| virtual [~TcpClient](./~tcpclient/)() | Förstör den aktuella instansen. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
