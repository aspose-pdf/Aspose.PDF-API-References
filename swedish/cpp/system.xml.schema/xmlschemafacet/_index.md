---
title: "System::Xml::Schema::XmlSchemaFacet class"
linktitle: "XmlSchemaFacet"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaFacet class. En basklass för alla facet som används när simple types härleds genom begränsning i C++."
type: docs
weight: 2900
url: /sv/cpp/system.xml.schema/xmlschemafacet/
---
## XmlSchemaFacet class


En basklass för alla facet som används när enkla typer härleds genom restriction.

```cpp
class XmlSchemaFacet : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_IsFixed](./get_isfixed/)() | Returnerar information som indikerar att detta facet är fast. |
| [get_Value](./get_value/)() | Returnerar **value**‑attributet för facetet. |
| virtual [set_IsFixed](./set_isfixed/)(bool) | Ställer in information som indikerar att detta facet är fast. |
| [set_Value](./set_value/)(const String\&) | Ställer in **value**-attributet för facetet. |
| [XmlSchemaFacet](./xmlschemafacet/)() | Initierar en ny instans av klassen [XmlSchemaFacet](./). |
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
