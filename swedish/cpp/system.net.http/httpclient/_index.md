---
title: "System::Net::Http::HttpClient-klass"
linktitle: "HttpClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpClient-klass. Representerar en basklass för en HTTP‑klient för att skicka begäranden och ta emot svar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.http/httpclient/
---
## HttpClient class


Representerar en basklass för en HTTP‑klient för att skicka begäranden och ta emot svar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekaren och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CancelPendingRequests](./cancelpendingrequests/)() | Avbryter alla pågående begäranden. |
| [get_BaseAddress](./get_baseaddress/)() | Hämtar basadressen för resursen som används för att skicka begäranden. |
| [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | RTTI-information. |
| [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | Hämtar det maximala antalet byte av svarsinnehåll. |
| [get_Timeout](./get_timeout/)() | Hämtar tidsintervallet att vänta innan begäran får timeout. |
| [HttpClient](./httpclient/)() | Skapar en ny instans. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>) | Skapar en ny instans. |
| [HttpClient](./httpclient/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Skapar en ny instans. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) | Skickar den angivna HTTP‑begäran. |
| [set_BaseAddress](./set_baseaddress/)(System::SharedPtr\<Uri\>) | Ställer in basadressen för resursen som används för att skicka begäranden. |
| [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(int64_t) | Ställer in det maximala antalet byte av svarsinnehåll. |
| [set_Timeout](./set_timeout/)(TimeSpan) | Ställer in tidsintervallet att vänta innan begäran får timeout. |
## Se även

* Class [HttpMessageInvoker](../httpmessageinvoker/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
