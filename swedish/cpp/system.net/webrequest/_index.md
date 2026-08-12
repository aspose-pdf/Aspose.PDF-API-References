---
title: "System::Net::WebRequest-klass"
linktitle: "WebRequest"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest-klass. Representerar en webbförfrågan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3800
url: /sv/cpp/system.net/webrequest/
---
## WebRequest class


Representerar en webbförfrågan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class WebRequest : public virtual System::Object
```

## Nested classes

* Class [HttpRequestCreator](./httprequestcreator/)
* Class [WebRequestPrefixElement](./webrequestprefixelement/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Abort](./abort/)() | Avbryter den aktuella förfrågan. |
| virtual [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron operation för att hämta en ström för att skriva data till resursen. |
| virtual [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) | Initierar en asynkron begäran för resursen. |
| static [Create](./create/)(String) | Skapar en ny instans av [WebRequest](./)-klassen med den angivna URI:n. |
| static [Create](./create/)(System::SharedPtr\<Uri\>) | Skapar en ny instans av [WebRequest](./)-klassen med den angivna URI:n. |
| static [CreateDefault](./createdefault/)(System::SharedPtr\<Uri\>) | Skapar en [WebRequest](./)-nedärvd klass för det angivna URI-schemat. |
| static [CreateHttp](./createhttp/)(String) | Skapar en ny instans av [WebRequest](./)-klassen med den angivna URI:n. |
| static [CreateHttp](./createhttp/)(System::SharedPtr\<Uri\>) | Skapar en ny instans av [WebRequest](./)-klassen med den angivna URI:n. |
| virtual [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona operationen för att hämta en ström är klar. |
| virtual [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) | Väntar tills den angivna asynkrona begäran för resursen är klar. |
| virtual [get_CachePolicy](./get_cachepolicy/)() | Hämtar cachepolicyn. |
| virtual [get_ConnectionGroupName](./get_connectiongroupname/)() | Hämtar namnet på anslutningsgruppen. |
| virtual [get_ContentLength](./get_contentlength/)() | Hämtar antalet byte av begärandedata som ska skickas. |
| virtual [get_ContentType](./get_contenttype/)() | Hämtar MIME‑typen för begäran. |
| virtual [get_Credentials](./get_credentials/)() | Hämtar autentiseringsinformation som är associerad med den aktuella begäran. |
| static [get_DefaultWebProxy](./get_defaultwebproxy/)() | Hämtar den globala HTTP-proxyn. |
| virtual [get_Headers](./get_headers/)() | Hämtar samlingen av HTTP‑huvuden. |
| virtual [get_Method](./get_method/)() | Hämtar HTTP‑metoden. |
| virtual [get_PreAuthenticate](./get_preauthenticate/)() | Hämtar ett värde som indikerar om begäran måste förautentiseras. |
| static [get_PrefixList](./get_prefixlist/)() | Hämtar prefixlistan. |
| virtual [get_Proxy](./get_proxy/)() | Hämtar HTTP‑proxyn. |
| virtual [get_RequestUri](./get_requesturi/)() | Returnerar begärans URI. |
| virtual [get_Timeout](./get_timeout/)() | Hämtar en tidsmängd i millisekunder efter vilken begäran kommer att tidsgränsas. |
| virtual [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Hämtar ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
| virtual [GetRequestStream](./getrequeststream/)() | Returnerar strömmen för att skriva data till resursen. |
| virtual [GetResponse](./getresponse/)() | Returnerar webbsvaret som är associerat med den aktuella webbförfrågan. |
| static [RegisterPrefix](./registerprefix/)(String, System::SharedPtr\<IWebRequestCreate\>) | Registrerar den [WebRequest](./)-nedärvda klassen för den angivna URI:n. |
| virtual [set_CachePolicy](./set_cachepolicy/)(System::SharedPtr\<System::Net::Cache::RequestCachePolicy\>) | Ställer in cachepolicyn. |
| virtual [set_ConnectionGroupName](./set_connectiongroupname/)(System::String) | Ställer in namnet på anslutningsgruppen. |
| virtual [set_ContentLength](./set_contentlength/)(int64_t) | Ställer in antalet byte av begärans data som ska skickas. |
| virtual [set_ContentType](./set_contenttype/)(String) | Ställer in MIME-typen för begäran. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Ställer in autentiseringsinformation som är associerad med den aktuella begäran. |
| static [set_DefaultWebProxy](./set_defaultwebproxy/)(System::SharedPtr\<IWebProxy\>) | Ställer in den globala HTTP-proxyn. |
| virtual [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) | Ställer in samlingen av HTTP-huvuden. |
| virtual [set_Method](./set_method/)(String) | Ställer in HTTP-metoden. |
| virtual [set_PreAuthenticate](./set_preauthenticate/)(bool) | Ställer in ett värde som indikerar om begäran måste vara förautentiserad. |
| static [set_PrefixList](./set_prefixlist/)(System::SharedPtr\<Collections::Generic::List\<System::SharedPtr\<WebRequest::WebRequestPrefixElement\>\>\>) | Ställer in prefixlistan. |
| virtual [set_Proxy](./set_proxy/)(System::SharedPtr\<IWebProxy\>) | Ställer in HTTP-proxyn. |
| virtual [set_Timeout](./set_timeout/)(int32_t) | Ställer in en tid i millisekunder efter vilken begäran får tidsgränsen. |
| virtual [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Ställer in ett värde som indikerar om egenskapen 'Credential' är lika med egenskapen 'DefaultCredentials'. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
