---
title: "System::Net::FileWebRequest-klass"
linktitle: "FileWebRequest"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::FileWebRequest-klass. Tillhandahåller en implementation av den abstrakta klassen WebRequest för att arbeta med filsystemet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.net/filewebrequest/
---
## FileWebRequest class


Tillhandahåller en implementation av den abstrakta klassen [WebRequest](../webrequest/) för att arbeta med filsystemet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Abort](./abort/)() override | Avbryter den aktuella förfrågan. |
| [BeginGetRequestStream](./begingetrequeststream/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron operation för att hämta en ström för att skriva data till resursen. |
| [BeginGetResponse](./begingetresponse/)(AsyncCallback, System::SharedPtr\<Object\>) override | Initierar en asynkron begäran för resursen. |
| [EndGetRequestStream](./endgetrequeststream/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona operationen för att hämta en ström är klar. |
| [EndGetResponse](./endgetresponse/)(System::SharedPtr\<IAsyncResult\>) override | Väntar tills den angivna asynkrona begäran för resursen är klar. |
| [FileWebRequest](./filewebrequest/)(System::SharedPtr\<Uri\>) | Skapar en ny instans. |
| [get_ContentType](./get_contenttype/)() override | Hämtar MIME‑typen för begäran. |
| [get_Headers](./get_headers/)() override | Hämtar samlingen av HTTP‑huvuden. |
| [get_Method](./get_method/)() override | Hämtar HTTP‑metoden. |
| [get_RequestUri](./get_requesturi/)() override | Returnerar begärans URI. |
| [GetResponse](./getresponse/)() override | Returnerar webbsvaret som är associerat med den aktuella webbförfrågan. |
| [set_ContentType](./set_contenttype/)(String) override | Ställer in MIME-typen för begäran. |
| [set_Headers](./set_headers/)(System::SharedPtr\<WebHeaderCollection\>) override | Ställer in samlingen av HTTP-huvuden. |
| [set_Method](./set_method/)(String) override | Ställer in HTTP-metoden. |
| [set_Timeout](./set_timeout/)(int) override | RTTI-information. |
## Se även

* Class [WebRequest](../webrequest/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
