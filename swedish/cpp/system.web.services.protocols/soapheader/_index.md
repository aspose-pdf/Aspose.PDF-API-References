---
title: "System::Web::Services::Protocols::SoapHeader class"
linktitle: "SoapHeader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::SoapHeader class. Representerar innehållet i SOAP‑huvudet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


Representerar innehållet i SOAP‑huvudet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SoapHeader : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Actor](./get_actor/)() | Hämtar URI:n för mottagaren av SOAP‑huvudet när SOAP‑version 1.1 används. |
| [get_DidUnderstand](./get_didunderstand/)() | Hämtar ett värde som indikerar om SOAP‑huvudet har behandlats korrekt. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Hämtar ett värde för attributet 'mustUnderstand' när SOAP‑version 1.1 används. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Hämtar ett värde för attributet 'mustUnderstand' när SOAP version 1.2 används. |
| [get_EncodedRelay](./get_encodedrelay/)() | Hämtar en strängrepresentation av attributvärdet 'relay'. |
| [get_MustUnderstand](./get_mustunderstand/)() | Hämtar ett värde som indikerar om SOAP‑huvudet måste förstås. |
| [get_Relay](./get_relay/)() | Hämtar ett värde för attributet 'relay'. |
| [get_Role](./get_role/)() | Hämtar URI:n för mottagaren av SOAP‑huvudet när SOAP version 1.2 används. |
| [set_Actor](./set_actor/)(String) | Ställer in URI:n för mottagaren av SOAP‑huvudet när SOAP version 1.1 används. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | Ställer in ett värde som indikerar om SOAP‑huvudet har behandlats korrekt. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | Ställer in ett värde för attributet 'mustUnderstand' när SOAP version 1.1 används. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | Ställer in ett värde för attributet 'mustUnderstand' när SOAP version 1.2 används. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | Ställer in en strängrepresentation av attributvärdet 'relay'. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | Ställer in ett värde som indikerar om SOAP‑huvudet måste förstås. |
| [set_Relay](./set_relay/)(bool) | Ställer in ett värde för attributet 'relay'. |
| [set_Role](./set_role/)(String) | Ställer in URI:n för mottagaren av SOAP‑huvudet när SOAP version 1.2 används. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Skapar en ny instans. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
