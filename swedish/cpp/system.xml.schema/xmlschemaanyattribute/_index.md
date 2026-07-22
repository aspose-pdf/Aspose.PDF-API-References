---
title: "System::Xml::Schema::XmlSchemaAnyAttribute-klass"
linktitle: "XmlSchemaAnyAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAnyAttribute-klass. Representerar World Wide Web Consortium (W3C) anyAttribute-elementet i C++."
type: docs
weight: 900
url: /sv/cpp/system.xml.schema/xmlschemaanyattribute/
---
## XmlSchemaAnyAttribute class


Representerar World Wide [Web](../../system.web/) Consortium (W3C) **anyAttribute**-elementet.

```cpp
class XmlSchemaAnyAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Returnerar namnutrymmena som innehåller de attribut som kan användas. |
| [get_ProcessContents](./get_processcontents/)() | Returnerar information om hur en applikation eller XML‑processor bör hantera valideringen av XML‑dokument för de attribut som anges av **anyAttribute**-elementet. |
| [set_Namespace](./set_namespace/)(const String\&) | Ställer in namnutrymmena som innehåller de attribut som kan användas. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Ställer in information om hur en applikation eller XML‑processor bör hantera valideringen av XML‑dokument för de attribut som anges av **anyAttribute**-elementet. |
| [XmlSchemaAnyAttribute](./xmlschemaanyattribute/)() | Initierar en ny instans av klassen [XmlSchemaAnyAttribute](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
