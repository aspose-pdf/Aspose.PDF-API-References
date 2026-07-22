---
title: "System::Web::Services::Protocols::SoapHttpClientProtocol klass"
linktitle: "SoapHttpClientProtocol"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapHttpClientProtocol klass. Klientproxytjänster måste ärva denna klass när SOAP används. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol class


Klientproxytjänsterna måste ärva denna klass när SOAP används. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Discover](./discover/)() | Binder den aktuella instansen till XML‑[Web](../../system.web/)-tjänsten. |
| [get_SoapVersion](./get_soapversion/)() | Hämtar SOAP‑versionen. |
| [InitializeSerializers](./initializeserializers/)(const System::TypeInfo\&, System::SharedPtr\<System::Xml::Serialization::XmlSerializerImplementation\>, String) | Initierar de interna fälten. |
| [set_SoapVersion](./set_soapversion/)(SoapProtocolVersion) | Ställer in SOAP‑versionen. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Skapar en ny instans. |
## Se även

* Class [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
