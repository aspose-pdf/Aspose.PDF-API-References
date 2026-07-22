---
title: "System::Web::Services::Protocols::HttpWebClientProtocol klass"
linktitle: "HttpWebClientProtocol"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::HttpWebClientProtocol klass. Denna basklass används i alla XML-webbtjänstklientproxier som använder HTTP. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol class


Denna basklass används i alla XML [Web](../../system.web/) tjänsteklientproxier som använder HTTP. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i pekaren [System::SmartPtr](../../system/smartptr/) och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CheckForCookies](./checkforcookies/)(System::SharedPtr\<Net::HttpWebResponse\>) | Lägger till cookies från den angivna begäran till den interna cookiebehållaren. |
| [get_AllowAutoRedirect](./get_allowautoredirect/)() | Hämtar ett värde som indikerar om klienten följer serveromdirigeringar. |
| [get_ClientCertificates](./get_clientcertificates/)() | Returnerar samlingen av klientcertifikaten. |
| [get_CookieContainer](./get_cookiecontainer/)() | Hämtar en behållare som används för att lagra cookies. |
| [get_EnableDecompression](./get_enabledecompression/)() | Hämtar ett värde som indikerar om dekomprimering är aktiverad. |
| [get_Proxy](./get_proxy/)() | Hämtar proxyinformation. |
| [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Hämtar ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| [get_UserAgent](./get_useragent/)() | Hämtar ett värde för 'User-Agent'-huvudet. |
| [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Ställer in ett värde som indikerar om klienten följer serveromdirigeringar. |
| [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Ställer in en behållare som används för att lagra cookies. |
| [set_EnableDecompression](./set_enabledecompression/)(bool) | Ställer in ett värde som indikerar om dekomprimering är aktiverad. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<Net::IWebProxy\>) | Ställer in proxyinformation. |
| [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(bool) | Ställer in ett värde som indikerar om anslutningsdelning är aktiverad när klienten använder NTLM-autentisering. |
| [set_UserAgent](./set_useragent/)(String) | Ställer in ett värde för 'User-Agent'-huvudet. |
| [UnregisterMapping](./unregistermapping/)(System::SharedPtr\<Object\>) |  |
## Se även

* Class [WebClientProtocol](../webclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
