---
title: "System::Net::WebResponse‑klass"
linktitle: "WebResponse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebResponse‑klass. Representerar ett webb‑svar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 4000
url: /sv/cpp/system.net/webresponse/
---
## WebResponse class


Representerar ett webb‑svar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class WebResponse : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | Stänger svarströmmen. |
| [Dispose](./dispose/)() override | Gör ingenting. |
| virtual [get_ContentLength](./get_contentlength/)() | RTTI-information. |
| virtual [get_ContentType](./get_contenttype/)() | Returnerar MIME‑typen för resursen. |
| virtual [get_Headers](./get_headers/)() | Returnerar samlingen av headerna som är associerade med det aktuella svaret. |
| virtual [get_ResponseUri](./get_responseuri/)() | Returnerar resursens URI. |
| virtual [get_SupportsHeaders](./get_supportsheaders/)() | Returnerar ett värde som indikerar om det aktuella svaret stödjer headern. |
| virtual [GetResponseStream](./getresponsestream/)() | Returnerar svarströmmen. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
