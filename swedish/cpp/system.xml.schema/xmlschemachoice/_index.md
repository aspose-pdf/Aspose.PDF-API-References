---
title: "System::Xml::Schema::XmlSchemaChoice klass"
linktitle: "XmlSchemaChoice"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaChoice-klass. Representerar choice‑elementet (kompositör) från XML‑schemat enligt World Wide Web Consortium (W3C). choice‑elementet tillåter endast ett av sina barn att förekomma i en instans i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice class


Representerar **choice**‑elementet (kompositör) från XML‑[Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). **choice**‑elementet tillåter endast ett av sina barn att förekomma i en instans.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Items](./get_items/)() override | Returnerar samlingen av element som ingår i kompositören (**choice**): [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/), eller [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaChoice](./xmlschemachoice/)() | Initierar en ny instans av klassen [XmlSchemaChoice](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaGroupBase](../xmlschemagroupbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
