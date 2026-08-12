---
title: "System::Net::Http::Headers::HttpRequestHeaders-klass"
linktitle: "HttpRequestHeaders"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpRequestHeaders-klass. Representerar samlingen av ''Request''-headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders class


Representerar samlingen av 'Request'-headern. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) override | Konkatenar den angivna HttpHeaders-klassens instans med den aktuella. |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Lägger till de kända headerna i den angivna samlingen. |
| [get_Accept](./get_accept/)() | RTTI-information. |
| [get_AcceptCharset](./get_acceptcharset/)() | Returnerar ett värde för 'Accept-Charset'-headern. |
| [get_AcceptEncoding](./get_acceptencoding/)() | Returnerar ett värde för 'Accept-Encoding'-headern. |
| [get_AcceptLanguage](./get_acceptlanguage/)() | Returnerar ett värde för 'Accept-Language'-headern. |
| [get_Authorization](./get_authorization/)() | Hämtar ett värde för 'Authorization'-huvudet. |
| [get_CacheControl](./get_cachecontrol/)() | Hämtar ett värde för 'Cache-Control'-huvudet. |
| [get_Connection](./get_connection/)() | Returnerar ett värde för 'Connection'-huvudet. |
| [get_ConnectionClose](./get_connectionclose/)() | Hämtar ett värde som indikerar om 'Connection'-huvudets värde innehåller 'Close'. |
| [get_Date](./get_date/)() | Hämtar ett värde för 'Date'-huvudet. |
| [get_Expect](./get_expect/)() | Returnerar värdet för 'Expect'-huvudet. |
| [get_ExpectContinue](./get_expectcontinue/)() | Hämtar ett värde som indikerar om 'Expect'-huvudets värde innehåller 'Continue'. |
| [get_From](./get_from/)() | Hämtar ett värde för 'From'-huvudet. |
| [get_Host](./get_host/)() | Hämtar ett värde för 'Host'-huvudet. |
| [get_IfMatch](./get_ifmatch/)() | Returnerar ett värde för 'If-Match'-huvudet. |
| [get_IfModifiedSince](./get_ifmodifiedsince/)() | Hämtar ett värde för 'If-Modified-Since'-huvudet. |
| [get_IfNoneMatch](./get_ifnonematch/)() | Returnerar ett värde för 'If-None-Match'-huvudet. |
| [get_IfRange](./get_ifrange/)() | Hämtar ett värde för 'If-Range'-huvudet. |
| [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | Hämtar ett värde för 'If-Unmodified-Since'-huvudet. |
| [get_MaxForwards](./get_maxforwards/)() | Hämtar ett värde för 'Max-Forwards'-huvudet. |
| [get_Pragma](./get_pragma/)() | Returnerar ett värde för 'Pragma'-huvudet. |
| [get_ProxyAuthorization](./get_proxyauthorization/)() | Hämtar ett värde för 'Proxy-Authorization'-huvudet. |
| [get_Range](./get_range/)() | Hämtar ett värde för '[Range](../../system/range/)'-huvudet. |
| [get_Referrer](./get_referrer/)() | Hämtar värdet för 'Referer'-huvudet. |
| [get_TE](./get_te/)() | Returnerar ett värde för 'TE'-huvudet. |
| [get_Trailer](./get_trailer/)() | Returnerar ett värde för 'Trailer'-huvudet. |
| [get_TransferEncoding](./get_transferencoding/)() | Returnerar ett värde för 'Transfer-Encoding'-huvudet. |
| [get_TransferEncodingChunked](./get_transferencodingchunked/)() | Hämtar ett värde som indikerar om 'Transfer-Encoding'-huvudets värde innehåller 'Chunked'. |
| [get_Upgrade](./get_upgrade/)() | Returnerar ett värde för 'Upgrade'-huvudet. |
| [get_UserAgent](./get_useragent/)() | Returnerar ett värde för 'User-Agent'-huvudet. |
| [get_Via](./get_via/)() | Returnerar ett värde för 'Via'-huvudet. |
| [get_Warning](./get_warning/)() | Returnerar ett värde för 'Warning'-huvudet. |
| [HttpRequestHeaders](./httprequestheaders/)() | Skapar en ny instans. |
| [set_Authorization](./set_authorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Ställer in ett värde för 'Authorization'-huvudet. |
| [set_CacheControl](./set_cachecontrol/)(System::SharedPtr\<CacheControlHeaderValue\>) | Ställer in ett värde för 'Cache-Control'-huvudet. |
| [set_ConnectionClose](./set_connectionclose/)(Nullable\<bool\>) | Ställer in ett värde som indikerar om 'Connection'-huvudets värde innehåller 'Close'. |
| [set_Date](./set_date/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'Date'-huvudet. |
| [set_ExpectContinue](./set_expectcontinue/)(Nullable\<bool\>) | Ställer in ett värde som indikerar om 'Expect'-huvudets värde innehåller 'Continue'. |
| [set_From](./set_from/)(String) | Ställer in ett värde för 'From'-huvudet. |
| [set_Host](./set_host/)(String) | Ställer in ett värde för 'Host'-huvudet. |
| [set_IfModifiedSince](./set_ifmodifiedsince/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'If-Modified-Since'-huvudet. |
| [set_IfRange](./set_ifrange/)(System::SharedPtr\<RangeConditionHeaderValue\>) | Ställer in ett värde för 'If-Range'-huvudet. |
| [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'If-Unmodified-Since'-huvudet. |
| [set_MaxForwards](./set_maxforwards/)(Nullable\<int32_t\>) | Ställer in ett värde för 'Max-Forwards'-huvudet. |
| [set_ProxyAuthorization](./set_proxyauthorization/)(System::SharedPtr\<AuthenticationHeaderValue\>) | Ställer in ett värde för 'Proxy-Authorization'-huvudet. |
| [set_Range](./set_range/)(System::SharedPtr\<RangeHeaderValue\>) | Ställer in ett värde för '[Range](../../system/range/)'-huvudet. |
| [set_Referrer](./set_referrer/)(System::SharedPtr\<Uri\>) | Ställer in ett värde för 'Referer'-huvudet. |
| [set_TransferEncodingChunked](./set_transferencodingchunked/)(Nullable\<bool\>) | Ställer in ett värde som indikerar om 'Transfer-Encoding'-huvudets värde innehåller 'Chunked'. |
## Se även

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
