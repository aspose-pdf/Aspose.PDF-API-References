---
title: "System::Net::Http::Headers::HttpResponseHeaders-klass"
linktitle: "HttpResponseHeaders"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpResponseHeaders-klass. Representerar samlingen av ''Response''-rubriker. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders class


Representerar samlingen av 'Response'-rubriker. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekaren och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Konkatenar den angivna HttpHeaders-klassens instans med den aktuella. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Lägger till de kända headerna i den angivna samlingen. |
| [get_AcceptRanges](./get_acceptranges/)() | RTTI-information. |
| [get_Age](./get_age/)() | Hämtar ett värde för 'Age'-rubriken. |
| [get_CacheControl](./get_cachecontrol/)() | Hämtar ett värde för 'Cache-Control'-huvudet. |
| [get_Connection](./get_connection/)() | Returnerar ett värde för 'Connection'-huvudet. |
| [get_ConnectionClose](./get_connectionclose/)() | Hämtar ett värde som indikerar om 'Connection'-huvudets värde innehåller 'Close'. |
| [get_Date](./get_date/)() | Hämtar ett värde för 'Date'-huvudet. |
| [get_ETag](./get_etag/)() | Hämtar ett värde för ''ETag''-huvudet. |
| [get_Location](./get_location/)() | Hämtar ett värde för 'Location'-rubriken. |
| [get_Pragma](./get_pragma/)() | Returnerar ett värde för 'Pragma'-huvudet. |
| [get_ProxyAuthenticate](./get_proxyauthenticate/)() | Returnerar ett värde för 'Proxy-Authenticate'-rubriken. |
| [get_RetryAfter](./get_retryafter/)() | Hämtar ett värde för 'Retry-After'-rubriken. |
| [get_Server](./get_server/)() | Returnerar ett värde för 'Server'-rubriken. |
| [get_Trailer](./get_trailer/)() | Returnerar ett värde för 'Trailer'-huvudet. |
| [get_TransferEncoding](./get_transferencoding/)() | Returnerar ett värde för 'Transfer-Encoding'-huvudet. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Hämtar ett värde som indikerar om 'Transfer-Encoding'-huvudets värde innehåller 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Returnerar ett värde för 'Upgrade'-huvudet. |
| [get_Vary](./get_vary/)() | Returnerar ett värde för 'Vary'-rubriken. |
| [get_Via](./get_via/)() | Returnerar ett värde för 'Via'-huvudet. |
| [get_Warning](./get_warning/)() | Returnerar ett värde för 'Warning'-huvudet. |
| [get_WwwAuthenticate](./get_wwwauthenticate/)() | Returnerar ett värde för 'WWW-Authenticate'-rubriken. |
| [HttpResponseHeaders](./httpresponseheaders/)() | Skapar en ny instans. |
| [set_Age](./set_age/)(Nullable\<TimeSpan\>) | Sätter ett värde för 'Age'-rubriken. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Ställer in ett värde för 'Cache-Control'-huvudet. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Ställer in ett värde som indikerar om 'Connection'-huvudets värde innehåller 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'Date'-huvudet. |
| [set_ETag](./set_etag/)(System::SharedPtr\<EntityTagHeaderValue\>) | Sätter ett värde för 'ETag'-rubriken. |
| [set_Location](./set_location/)(System::SharedPtr\<Uri\>) | Sätter ett värde för 'Location'-rubriken. |
| [set_RetryAfter](./set_retryafter/)(System::SharedPtr\<RetryConditionHeaderValue\>) | Sätter ett värde för 'Retry-After'-rubriken. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Ställer in ett värde som indikerar om 'Transfer-Encoding'-huvudets värde innehåller 'Chunked'. |
## Se även

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
