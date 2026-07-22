---
title: "System::Net::HttpWebRequest klass"
linktitle: "HttpWebRequest"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::HttpWebRequest klass. Representerar HTTP‑webbförfrågan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2000
url: /sv/cpp/system.net/httpwebrequest/
---
## HttpWebRequest class


Representerar HTTP‑webbförfrågan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Abort](./abort/)() override | Avbryter den aktuella förfrågan. |
| virtual [AddRange](./addrange/)(int32_t) | Lägger till '[Range](../../system/range/)'‑huvudet till den aktuella förfrågan. |
| virtual [AddRange](./addrange/)(System::String, int32_t, int32_t) | Lägger till '[Range](../../system/range/)'‑huvudet till den aktuella förfrågan. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron operation för att hämta en ström för att skriva data till resursen. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron begäran för resursen. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona operationen för att hämta en ström är klar. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona begäran för resursen är klar. |
| [get_Accept](./get_accept/)() | Hämtar värdet för HTTP‑huvudet 'Accept'. |
| virtual [get_AllowAutoRedirect](./get_allowautoredirect/)() | Hämtar ett värde som indikerar om begäran ska följa omdirigeringar. |
| virtual [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Hämtar ett värde som indikerar om data som mottas från resursen måste buffras. |
| virtual [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Hämtar ett värde som indikerar om buffring är aktiverad för att skicka data. |
| virtual [get_ClientCertificates](./get_clientcertificates/)() | Hämtar samlingen av certifikat som är associerade med den aktuella begäran. |
| [get_ConnectionGroupName](./get_connectiongroupname/)() override | Hämtar namnet på anslutningsgruppen. |
| [get_ContentLength](./get_contentlength/)() override | Hämtar antalet byte av begärandedata som ska skickas. |
| [get_ContentType](./get_contenttype/)() override | Hämtar MIME‑typen för begäran. |
| [get_ContinueTimeout](./get_continuetimeout/)() | Hämtar en tidsgräns för att vänta tills statuskoden 100‑Continue mottas. |
| virtual [get_CookieContainer](./get_cookiecontainer/)() | Hämtar en cookie‑behållare som är associerad med den aktuella webb‑begäran. |
| [get_Credentials](./get_credentials/)() override | Hämtar autentiseringsinformation som är associerad med den aktuella begäran. |
| virtual [get_HaveResponse](./get_haveresponse/)() | Returnerar ett värde som indikerar om ett svar har mottagits. |
| [get_Headers](./get_headers/)() override | Hämtar samlingen av HTTP‑huvuden. |
| virtual [get_KeepAlive](./get_keepalive/)() | Hämtar ett värde som indikerar om den aktuella begäran måste innehålla 'Keep-Alive'-huvudet. |
| virtual [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Hämtar det maximala antalet tillåtna omdirigeringar. |
| [get_Method](./get_method/)() override | Hämtar HTTP‑metoden. |
| [get_PreAuthenticate](./get_preauthenticate/)() override | Hämtar ett värde som indikerar om begäran måste förautentiseras. |
| [get_Proxy](./get_proxy/)() override | Hämtar HTTP‑proxyn. |
| virtual [get_Referer](./get_referer/)() | Hämtar värdet för 'Referer'-huvudet. |
| [get_RequestUri](./get_requesturi/)() override | Returnerar begärans URI. |
| virtual [get_SendChunked](./get_sendchunked/)() | Hämtar ett värde som indikerar om data måste skickas i segment. |
| [get_ServicePoint](./get_servicepoint/)() | Returnerar en servicepunkt som representerar nätverksanslutningen till resursen. |
| virtual [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Returnerar ett värde som indikerar om den aktuella begäran kan använda en cookiebehållare. |
| [get_Timeout](./get_timeout/)() override | Hämtar en tidsmängd i millisekunder efter vilken begäran kommer att tidsgränsas. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Hämtar ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| virtual [get_UserAgent](./get_useragent/)() | Hämtar ett värde för 'User-Agent'-huvudet. |
| [GetRequestStream](./getrequeststream/)() override | Returnerar strömmen för att skriva data till resursen. |
| [GetResponse](./getresponse/)() override | Returnerar webbsvaret som är associerat med den aktuella webbförfrågan. |
| [HttpWebRequest](./httpwebrequest/)(System::SharedPtr\<Uri\>) | Skapar en ny instans. |
| [set_Accept](./set_accept/)(String) | Ställer in värdet för HTTP-huvudet 'Accept'. |
| virtual [set_AllowAutoRedirect](./set_allowautoredirect/)(bool) | Ställer in ett värde som indikerar om begäran ska följa omdirigeringar. |
| virtual [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(bool) | Ställer in ett värde som indikerar om data som tas emot från resursen måste buffras. |
| virtual [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(bool) | Ställer in ett värde som indikerar om buffring är aktiverad för att skicka data. |
| virtual [set_ClientCertificates](./set_clientcertificates/)(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>) | Ställer in samlingen av certifikat som är associerade med den aktuella begäran. |
| [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) override | Ställer in namnet på anslutningsgruppen. |
| [set_ContentLength](./set_contentlength/)(int64_t) override | Ställer in antalet byte av begärans data som ska skickas. |
| [set_ContentType](./set_contenttype/)(String) override | Ställer in MIME-typen för begäran. |
| [set_ContinueTimeout](./set_continuetimeout/)(int32_t) | Ställer in en tidsgräns för att vänta tills statuskoden 100-Continue mottas. |
| virtual [set_CookieContainer](./set_cookiecontainer/)(System::SharedPtr\<System::Net::CookieContainer\>) | Ställer in en cookiebehållare som är associerad med den aktuella webbförfrågan. |
| [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) override | Ställer in autentiseringsinformation som är associerad med den aktuella begäran. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Ställer in samlingen av HTTP-huvuden. |
| virtual [set_KeepAlive](./set_keepalive/)(bool) | Ställer in ett värde som indikerar om den aktuella begäran måste innehålla 'Keep-Alive'-huvudet. |
| virtual [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Ställer in ett maximalt antal tillåtna omdirigeringar. |
| [set_Method](./set_method/)(String) override | Ställer in HTTP-metoden. |
| [set_PreAuthenticate](./set_preauthenticate/)(bool) override | Ställer in ett värde som indikerar om begäran måste vara förautentiserad. |
| [set_ProtocolVersion](./set_protocolversion/)(System::Version) | RTTI-information. |
| [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) override | Ställer in HTTP-proxyn. |
| virtual [set_Referer](./set_referer/)(System::String) | Ställer in ett värde för 'Referer'-huvudet. |
| virtual [set_SendChunked](./set_sendchunked/)(bool) | Ställer in ett värde som indikerar om data måste skickas i segment. |
| [set_Timeout](./set_timeout/)(int) override | Ställer in en tid i millisekunder efter vilken begäran får tidsgränsen. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) override | Ställer in ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| virtual [set_UserAgent](./set_useragent/)(System::String) | Ställer in ett värde för 'User-Agent'-huvudet. |
## Se även

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
