---
title: "System::Xml::Schema::XmlSchemaGroup-klass"
linktitle: "XmlSchemaGroup"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaGroup-klass. Representerar gruppelementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass definierar grupper på schemanivå som refereras från de komplexa typerna. Den grupperar en uppsättning elementdeklarationer så att de kan införlivas som en grupp i definitioner av komplexa typer i C++."
type: docs
weight: 3100
url: /sv/cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


Representerar **group**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass definierar grupper på **schema**-nivå som refereras från de komplexa typerna. Den grupperar en uppsättning elementdeklarationer så att de kan införlivas som en grupp i definitioner av komplexa typer.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Name](./get_name/)() | Returnerar namnet på schemagrupper. |
| [get_Particle](./get_particle/)() | Returnerar en av klasserna [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [get_QualifiedName](./get_qualifiedname/)() | Returnerar det kvalificerade namnet på schemagrupper. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på schemagrupper. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | Ställer in en av klasserna [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaGroup](./xmlschemagroup/)() | Initierar en ny instans av klassen [XmlSchemaGroup](./). |
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
