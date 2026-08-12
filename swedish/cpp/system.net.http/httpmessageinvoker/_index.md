---
title: "System::Net::Http::HttpMessageInvoker class"
linktitle: "HttpMessageInvoker"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpMessageInvoker-klass. Tillåter applikationer att anropa Send‑metoden på en HTTP‑hanteringskedja. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Tillåter applikationer att anropa Send‑metoden i en HTTP‑hanterarkedja. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Avslutar den aktuella instansen. Denna metod avslutar också hanteraren om det krävs. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | RTTI-information. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Skapar en ny instans. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Skickar den angivna begäran. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
