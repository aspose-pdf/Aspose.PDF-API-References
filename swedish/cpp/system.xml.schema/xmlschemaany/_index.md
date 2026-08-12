---
title: "System::Xml::Schema::XmlSchemaAny klass"
linktitle: "XmlSchemaAny"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAny klass. Representerar World Wide Web Consortium (W3C) any-elementet i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny class


Representerar World Wide [Web](../../system.web/) Consortium (W3C) **any**-elementet.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Returnerar de namnrymder som innehåller de element som kan användas. |
| [get_ProcessContents](./get_processcontents/)() | Returnerar information om hur en applikation eller XML‑processor bör hantera valideringen av XML‑dokument för de element som anges av **any**‑elementet. |
| [set_Namespace](./set_namespace/)(const String\&) | Ställer in namnrymderna som innehåller de element som kan användas. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Ställer in information om hur en applikation eller XML‑processor bör hantera valideringen av XML‑dokument för de element som anges av **any**‑elementet. |
| [XmlSchemaAny](./xmlschemaany/)() | Initierar en ny instans av klassen [XmlSchemaAny](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
