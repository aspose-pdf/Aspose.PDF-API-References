---
title: "System::Net::WebClient‑klass"
linktitle: "WebClient"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebClient‑klass. WebClient tillhandahåller vanliga metoder för att skicka och ta emot data. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3500
url: /sv/cpp/system.net/webclient/
---
## WebClient class


[WebClient](./) provides common methods for sending and receiving data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClient : public System::ComponentModel::Component
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DownloadData](./downloaddata/)(const String\&) const | Laddar ner den angivna resursen som en byte‑array. |
| [DownloadData](./downloaddata/)(const SharedPtr\<Uri\>\&) const | Laddar ner den angivna resursen som en byte‑array. |
| [DownloadString](./downloadstring/)(const String\&) const | Laddar ner den angivna resursen som en sträng. |
| [DownloadString](./downloadstring/)(const SharedPtr\<Uri\>\&) const | Laddar ner den angivna resursen som en sträng. |
| [get_Encoding](./get_encoding/)() const | Hämtar den kodning som används för att ladda ner eller ladda upp strängar. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<Text::Encoding\>\&) | Ställer in den kodning som används för att ladda ner eller ladda upp strängar. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | INTE IMPLEMENTERAD. |
| [WebClient](./webclient/)() | RTTI-information. |
| [~WebClient](./~webclient/)() | Förstör den aktuella instansen. |
## Se även

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
