---
title: "System::Net::Http::Headers::HttpContentHeaders class"
linktitle: "HttpContentHeaders"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpContentHeaders class. Representerar samlingen av ''Content''-rubriker. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.http.headers/httpcontentheaders/
---
## HttpContentHeaders class


Representerar samlingen av 'Content'-rubriker. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [AddKnownHeaders](./addknownheaders/)(System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) | Lägger till de kända headerna i den angivna samlingen. |
| [get_Allow](./get_allow/)() | RTTI-information. |
| [get_ContentDisposition](./get_contentdisposition/)() | Hämtar ett värde för 'Content-Disposition'-rubriken. |
| [get_ContentEncoding](./get_contentencoding/)() | Hämtar ett värde för 'Content-Encoding'-rubriken. |
| [get_ContentLanguage](./get_contentlanguage/)() | Hämtar ett värde för 'Content-Language'-rubriken. |
| [get_ContentLength](./get_contentlength/)() | Hämtar ett värde för 'Content-Length'-rubriken. |
| [get_ContentLocation](./get_contentlocation/)() | Hämtar ett värde för 'Content-Location'-rubriken. |
| [get_ContentMD5](./get_contentmd5/)() | Hämtar ett värde för 'Content-MD5'-rubriken. |
| [get_ContentRange](./get_contentrange/)() | Hämtar ett värde för 'Content-Range'-rubriken. |
| [get_ContentType](./get_contenttype/)() | Hämtar ett värde för 'Content-Type'-rubriken. |
| [get_Expires](./get_expires/)() | Hämtar ett värde för 'Expires'-rubriken. |
| [get_LastModified](./get_lastmodified/)() | Hämtar ett värde för 'Last-Modified'-huvudet. |
| [HttpContentHeaders](./httpcontentheaders/)(HeaderFunc\<Nullable\<int64_t\>\>) | Skapar en ny instans. |
| [set_ContentDisposition](./set_contentdisposition/)(System::SharedPtr\<ContentDispositionHeaderValue\>) | Ställer in ett värde för 'Content-Disposition'-huvudet. |
| [set_ContentLength](./set_contentlength/)(Nullable\<int64_t\>) | Ställer in ett värde för 'Content-Length'-huvudet. |
| [set_ContentLocation](./set_contentlocation/)(System::SharedPtr\<Uri\>) | Ställer in ett värde för 'Content-Location'-huvudet. |
| [set_ContentMD5](./set_contentmd5/)(System::ArrayPtr\<uint8_t\>) | Ställer in ett värde för 'Content-MD5'-huvudet. |
| [set_ContentRange](./set_contentrange/)(System::SharedPtr\<ContentRangeHeaderValue\>) | Ställer in ett värde för 'Content-Range'-huvudet. |
| [set_ContentType](./set_contenttype/)(System::SharedPtr\<MediaTypeHeaderValue\>) | Ställer in ett värde för 'Content-Type'-huvudet. |
| [set_Expires](./set_expires/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'Expires'-huvudet. |
| [set_LastModified](./set_lastmodified/)(Nullable\<DateTimeOffset\>) | Ställer in ett värde för 'Last-Modified'-huvudet. |
## Se även

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
