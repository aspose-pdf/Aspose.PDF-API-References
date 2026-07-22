---
title: "System::Net::WebRequest::HttpRequestCreator klass"
linktitle: "HttpRequestCreator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest::HttpRequestCreator klass. Skapar WebRequest‑klassens instanser. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3900
url: /sv/cpp/system.net/webrequest/httprequestcreator/
---
## HttpRequestCreator class


Skapar WebRequest‑klassens instanser. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpRequestCreator : public System::Net::IWebRequestCreate
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<Uri\>) | Skapar en ny instans av WebRequest‑klassen med den angivna URI:n. |
## Se även

* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
