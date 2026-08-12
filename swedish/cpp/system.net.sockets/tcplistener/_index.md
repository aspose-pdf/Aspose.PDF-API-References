---
title: "System::Net::Sockets::TcpListener class"
linktitle: "TcpListener"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::TcpListener class. Representerar en lyssnare för TCP-nätverkstjänster. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.sockets/tcplistener/
---
## TcpListener class


Representerar en lyssnare för TCP-nätverkstjänster. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TcpListener : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AcceptSocket](./acceptsocket/)() | Accepterar den väntande anslutningsförfrågan och returnerar socketen som används för att skicka och ta emot data. |
| [AcceptTcpClient](./accepttcpclient/)() | Accepterar den väntande anslutningsförfrågan och returnerar TcpClient-klassens instans som används för att skicka och ta emot data. |
| [AllowNatTraversal](./allownattraversal/)(bool) | Aktiverar eller inaktiverar NAT-traversering. |
| [BeginAcceptSocket](./beginacceptsocket/)(AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron accept-operation. |
| [BeginAcceptTcpClient](./beginaccepttcpclient/)(AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron accept-operation. |
| static [Create](./create/)(int32_t) | Skapar en ny instans med det specificerade portnumret. |
| [EndAcceptSocket](./endacceptsocket/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den specificerade asynkrona accept-operationen är klar. |
| [EndAcceptTcpClient](./endaccepttcpclient/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den specificerade asynkrona accept-operationen är klar. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Hämtar ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| [get_LocalEndpoint](./get_localendpoint/)() | Returnerar den underliggande slutpunkten. |
| [get_Server](./get_server/)() | RTTI-information. |
| [Pending](./pending/)() | Returnerar ett värde som indikerar om det finns väntande anslutningsförfrågningar. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Ställer in ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| [Start](./start/)() | Startar lyssning på inkommande anslutningar. |
| [Start](./start/)(int32_t) | Startar lyssning på inkommande anslutningar. |
| [Stop](./stop/)() | Stoppar lyssning på inkommande anslutningar. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPEndPoint\>) | Skapar en ny instans. |
| [TcpListener](./tcplistener/)(System::SharedPtr\<IPAddress\>, int32_t) | Skapar en ny instans. |
| [TcpListener](./tcplistener/)(int32_t) | Skapar en ny instans. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
