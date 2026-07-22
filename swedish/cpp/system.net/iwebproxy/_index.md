---
title: "System::Net::IWebProxy klass"
linktitle: "IWebProxy"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::IWebProxy klass. Detta gränssnitt används för implementering av proxyåtkomst till WebRequest‑klassen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2700
url: /sv/cpp/system.net/iwebproxy/
---
## IWebProxy class


Detta gränssnitt används för implementering av proxyåtkomst till [WebRequest](../webrequest/)-klassen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class IWebProxy : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_Credentials](./get_credentials/)() | RTTI-information. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Returnerar proxy‑URI:n. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Returnerar ett värde som indikerar om proxy inte får användas för den angivna värden. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Ställer in autentiseringsuppgifter för proxyservern. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
