---
title: "System::Net::Http::HttpResponseMessage-klass"
linktitle: "HttpResponseMessage"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpResponseMessage-klass. Representerar ett HTTP‑svarsmeddelande. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.net.http/httpresponsemessage/
---
## HttpResponseMessage class


Representerar ett HTTP‑svarsmeddelande. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Avslutar den aktuella instansen. Denna metod avslutar också innehållet i HTTP‑svaret. |
| [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | Kontrollerar statuskoden. [HttpRequestException](../httprequestexception/) kommer att kastas när statuskoden inte tillhör 2xx. |
| [get_Content](./get_content/)() const | Hämtar innehållet i HTTP‑svaret. |
| [get_Headers](./get_headers/)() const | Returnerar HTTP‑innehållshuvudena. |
| [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | Kontrollerar om statuskoden indikerar att åtgärden som begärdes av klienten mottogs, förstås och accepterades. |
| [get_ReasonPhrase](./get_reasonphrase/)() const | Hämtar Reason-Phrase som skickas av servrar tillsammans med statuskoden. |
| [get_RequestMessage](./get_requestmessage/)() const | Hämtar HTTP‑begäranmeddelandet. |
| [get_StatusCode](./get_statuscode/)() const | Hämtar HTTP‑statuskoden. |
| [get_Version](./get_version/)() const | RTTI-information. |
| [HttpResponseMessage](./httpresponsemessage/)() | Skapar en ny instans. |
| [HttpResponseMessage](./httpresponsemessage/)(HttpStatusCode) | Skapar en ny instans. |
| [set_Content](./set_content/)(System::SharedPtr\<HttpContent\>) | Ställer in innehållet i HTTP‑svaret. |
| [set_ReasonPhrase](./set_reasonphrase/)(String) | Ställer in Reason-Phrase som skickas av servrar tillsammans med statuskoden. |
| [set_RequestMessage](./set_requestmessage/)(System::SharedPtr\<HttpRequestMessage\>) | Ställer in HTTP‑begäranmeddelandet. |
| [set_StatusCode](./set_statuscode/)(HttpStatusCode) | Ställer in HTTP‑statuskoden. |
| [set_Version](./set_version/)(System::Version) | Ställer in HTTP‑versionen. |
| [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
