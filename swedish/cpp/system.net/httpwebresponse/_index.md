---
title: "System::Net::HttpWebResponse-klass"
linktitle: "HttpWebResponse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::HttpWebResponse-klass. Representerar HTTP‑webbresponsen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.net/httpwebresponse/
---
## HttpWebResponse class


Representerar HTTP‑webbresponsen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpWebResponse : public System::Net::WebResponse
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger svarströmmen. |
| [get_CharacterSet](./get_characterset/)() | Ej implementerad. |
| [get_ContentLength](./get_contentlength/)() override | RTTI-information. |
| [get_ContentType](./get_contenttype/)() override | Returnerar MIME‑typen för resursen. |
| virtual [get_Cookies](./get_cookies/)() | Returnerar cookies som är associerade med webbsvaret. |
| [get_Headers](./get_headers/)() override | Returnerar samlingen av headerna som är associerade med det aktuella svaret. |
| virtual [get_Method](./get_method/)() | Returnerar HTTP‑metoden. |
| [get_ResponseUri](./get_responseuri/)() override | Returnerar resursens URI. |
| virtual [get_StatusCode](./get_statuscode/)() | Returnerar HTTP‑statuskoden som är associerad med webbsvaret. |
| virtual [get_StatusDescription](./get_statusdescription/)() | Returnerar strängrepresentationen av statuskoden. |
| [get_SupportsHeaders](./get_supportsheaders/)() override | Returnerar ett värde som indikerar om det aktuella svaret stödjer headern. |
| [GetResponseHeader](./getresponseheader/)(String) | Returnerar det motsvarande värdet för det angivna rubriknamnet. |
| [GetResponseStream](./getresponsestream/)() override | Returnerar svarströmmen. |
| [HttpWebResponse](./httpwebresponse/)(System::SharedPtr\<Http::HttpResponseMessage\>, System::SharedPtr\<Uri\>, System::SharedPtr\<CookieContainer\>) | Skapar en ny instans. |
## Se även

* Class [WebResponse](../webresponse/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
