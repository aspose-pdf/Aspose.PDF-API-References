---
title: "System::Web::Services::Protocols::SoapHeaderAttribute klass"
linktitle: "SoapHeaderAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapHeaderAttribute klass. Anger SOAP‑huvudet som XML‑Web‑tjänstemetoden eller XML‑Web‑tjänsteklienten kan bearbeta. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute class


Anger SOAP‑huvudet som XML‑[Web](../../system.web/)-tjänstemetoden eller XML‑[Web](../../system.web/)-tjänsteklienten kan bearbeta. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Direction](./get_direction/)() | RTTI-information. |
| [get_MemberName](./get_membername/)() | Hämtar namnet på en medlemsvariabel i XML‑SOAP‑tjänsten som används för att ta emot SOAP‑huvudinnehållet. |
| [get_Required](./get_required/)() | Hämtar ett värde som indikerar om SOAP‑huvudet måste förstås och bearbetas av mottagar‑XML‑[Web](../../system.web/)-tjänsten eller XML‑[Web](../../system.web/)-tjänsteklienten. |
| [set_Direction](./set_direction/)(SoapHeaderDirection) | Ställer in SOAP‑huvudets riktning. |
| [set_MemberName](./set_membername/)(String) | Ställer in namnet på en medlemsvariabel i XML‑SOAP‑tjänsten som används för att ta emot SOAP‑huvudinnehållet. |
| [set_Required](./set_required/)(bool) | Ställer in ett värde som indikerar om SOAP‑huvudet måste förstås och bearbetas av mottagar‑XML‑[Web](../../system.web/)-tjänsten eller XML‑[Web](../../system.web/)-tjänsteklienten. |
| [SoapHeaderAttribute](./soapheaderattribute/)(String) | Skapar en ny instans. |
## Se även

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
