---
title: "System::Web::Services::Protocols::SoapDocumentServiceAttribute-klass"
linktitle: "SoapDocumentServiceAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapDocumentServiceAttribute-klass. Anger standardformatet för SOAP‑förfrågningar och -svar. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute class


Anger standardformatet för SOAP‑förfrågningar och -svar. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ParameterStyle](./get_parameterstyle/)() | RTTI-information. |
| [get_RoutingStyle](./get_routingstyle/)() | Hämtar ett värde som visar hur SOAP‑meddelanden routas till tjänsten. |
| [get_Use](./get_use/)() | Hämtar parameterformateringen. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Ställer in ett värde som indikerar om parametrar är kapslade i ett enda XML-element under 'Body'-elementet. |
| [set_RoutingStyle](./set_routingstyle/)(SoapServiceRoutingStyle) | Anger ett värde som visar hur SOAP‑meddelanden routas till tjänsten. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Anger parameterformateringen. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Skapar en ny instans. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse) | Skapar en ny instans. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse, SoapParameterStyle) | Skapar en ny instans. |
## Se även

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
