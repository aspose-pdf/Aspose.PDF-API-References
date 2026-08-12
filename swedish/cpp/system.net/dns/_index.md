---
title: "System::Net::Dns class"
linktitle: "Dns"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Dns class. Tillhandahåller metoder för att arbeta med DNS i C++."
type: docs
weight: 700
url: /sv/cpp/system.net/dns/
---
## Dns class


Tillhandahåller metoder för att arbeta med DNS.

```cpp
class Dns : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [BeginGetHostAddresses](./begingethostaddresses/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [BeginGetHostByName](./begingethostbyname/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med det angivna värdnamnet. |
| static [BeginGetHostEntry](./begingethostentry/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [BeginGetHostEntry](./begingethostentry/)(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med den angivna IP-adressen. |
| static [BeginResolve](./beginresolve/)(String, AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-class-instans med det angivna värdnamnet. |
| [Dns](./dns/)() | Den borttagna standardkonstruktorn. |
| static [EndGetHostAddresses](./endgethostaddresses/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar. |
| static [EndGetHostByName](./endgethostbyname/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar. |
| static [EndGetHostEntry](./endgethostentry/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar. |
| static [EndResolve](./endresolve/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar. |
| static [GetHostAddresses](./gethostaddresses/)(String) | Returnerar en samling IP-adresser för det angivna värdnamnet eller IP-adressen. |
| static [GetHostByAddress](./gethostbyaddress/)(String) | Skapar en ny IPHostEntry-class-instans med den angivna strängrepresentationen av en IP-adress. |
| static [GetHostByAddress](./gethostbyaddress/)(System::SharedPtr\<IPAddress\>) | Skapar en ny IPHostEntry-class-instans med den angivna IP-adressen. |
| static [GetHostByName](./gethostbyname/)(String) | RTTI-information. |
| static [GetHostEntry](./gethostentry/)(String) | Skapar en ny IPHostEntry-class-instans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [GetHostEntry](./gethostentry/)(System::SharedPtr\<IPAddress\>) | Skapar en ny IPHostEntry-class-instans med den angivna IP-adressen. |
| static [GetHostName](./gethostname/)() | Returnerar värdnamnet för den lokala maskinen. |
| static [Resolve](./resolve/)(String) | Skapar en ny IPHostEntry-class-instans med det angivna värdnamnet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
