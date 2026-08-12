---
title: "System::Web::Services::Protocols::SoapClientMessage class"
linktitle: "SoapClientMessage"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapClientMessage class. Representerar data i en SOAP-förfrågan som skickas eller ett SOAP-svar som tas emot. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Representerar data i en SOAP‑förfrågan som skickas eller ett SOAP‑svar som tas emot. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Action](./get_action/)() override | Returnerar ett värde för attributet 'SOAPAction'. |
| [get_Client](./get_client/)() | Returnerar en instans av klientproxyklassen. |
| virtual [get_OneWay](./get_oneway/)() | Returnerar ett värde som indikerar om en klient inte väntar på att en server ska slutföra bearbetningen av en metod. |
| [get_SoapVersion](./get_soapversion/)() override | Returnerar den SOAP‑version som används. |
| [get_Url](./get_url/)() override | Returnerar XML [Web](../../system.web/) tjänstens URL. |
| [SoapClientMessage](./soapclientmessage/)(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Skapar en ny instans. |
## Se även

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
