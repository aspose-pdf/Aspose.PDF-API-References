---
title: "System::Net::Http::HttpClientHandler class"
linktitle: "HttpClientHandler"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpClientHandler-klass. Representerar standardmeddelandehanteraren som används av HttpClient-klassen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.net.http/httpclienthandler/
---
## HttpClientHandler class


Representerar standardmeddelandehanteraren som används av [HttpClient](../httpclient/)-klassen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpClientHandler : public System::Net::Http::HttpMessageHandler
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Gör ingenting. |
| [get_CookieContainer](./get_cookiecontainer/)() | Hämtar cookie-behållaren som används för att lagra servercookies. |
| [get_Credentials](./get_credentials/)() | Hämtar autentiseringsinformationen. |
| [HttpClientHandler](./httpclienthandler/)() | RTTI-information. |
| [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) override | RTTI-information. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Ställer in cookie-behållaren som används för att lagra servercookies. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Ställer in autentiseringsinformationen. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Ställer in proxyinformationen. |
| [set_Timeout](./set_timeout/)(int32_t) | Hämtar en tidsmängd i millisekunder efter vilken begäran kommer att tidsgränsas. |
| [set_UseCookies](./set_usecookies/)(bool) | Ställer in värdet som indikerar om den aktuella instansen använder cookie-behållaren för att lagra servercookies och om instansen använder servercookies när den skickar begäranden. |
| [set_UseProxy](./set_useproxy/)(bool) | Ställer in värdet som indikerar om den aktuella instansen använder proxy för att skicka begäranden. |
## Se även

* Class [HttpMessageHandler](../httpmessagehandler/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
