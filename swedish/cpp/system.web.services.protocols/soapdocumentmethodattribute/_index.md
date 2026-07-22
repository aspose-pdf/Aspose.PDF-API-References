---
title: "System::Web::Services::Protocols::SoapDocumentMethodAttribute klass"
linktitle: "SoapDocumentMethodAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapDocumentMethodAttribute-klass. Anger att alla SOAP‑meddelanden som skickas till eller returneras från metoden använder dokumentformatet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute class


Anger att alla SOAP‑meddelanden som skickas till eller returneras från metoden använder dokumentformatet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Action](./get_action/)() | RTTI-information. |
| [get_Binding](./get_binding/)() | Hämtar bindningen för vilken en XML‑webbtjänstmetod implementerar en operation. |
| [get_OneWay](./get_oneway/)() | Hämtar ett värde som indikerar om en klient inte väntar på att servern ska slutföra bearbetningen av en metod. |
| [get_ParameterStyle](./get_parameterstyle/)() | Hämtar ett värde som indikerar om parametrar är inkapslade i ett enda XML‑element under 'Body'-elementet. |
| [get_RequestElementName](./get_requestelementname/)() | Hämtar namnet på XML‑elementet som är associerat med SOAP‑begäran, vilket definieras i en tjänstebeskrivning som en operation. |
| [get_RequestNamespace](./get_requestnamespace/)() | Hämtar namnutrymmet som är associerat med SOAP‑begäran. |
| [get_ResponseElementName](./get_responseelementname/)() | Hämtar namnet på XML‑elementet som är associerat med SOAP‑svaret. |
| [get_ResponseNamespace](./get_responsenamespace/)() | Hämtar namnutrymmet som är associerat med SOAP‑svaret. |
| [get_Use](./get_use/)() | Hämtar ett värde som bestämmer meddelandekodningsmetoden. |
| [set_Action](./set_action/)(String) | Ställer in ett värde för attributet 'SOAPAction'. |
| [set_Binding](./set_binding/)(String) | Ställer in bindningen för vilken en XML-webbtjänstmetod implementerar en operation. |
| [set_OneWay](./set_oneway/)(bool) | Ställer in ett värde som indikerar om klienten inte väntar på att servern ska slutföra bearbetningen av en metod. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Ställer in ett värde som indikerar om parametrar är kapslade i ett enda XML-element under 'Body'-elementet. |
| [set_RequestElementName](./set_requestelementname/)(String) | Ställer in namnet på XML-elementet som är associerat med SOAP-förfrågan, vilket definieras i en tjänstebeskrivning som en operation. |
| [set_RequestNamespace](./set_requestnamespace/)(String) | Ställer in namnutrymmet som är associerat med SOAP-förfrågan. |
| [set_ResponseElementName](./set_responseelementname/)(String) | Ställer in namnet på XML-elementet som är associerat med SOAP-svaret. |
| [set_ResponseNamespace](./set_responsenamespace/)(String) | Ställer in namnutrymmet som är associerat med SOAP-svaret. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Ställer in ett värde som bestämmer meddelandekodningsmetoden. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Skapar en ny instans. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)(String) | Skapar en ny instans. |
## Se även

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
