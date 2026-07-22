---
title: "System::Xml::Schema::XmlSchemaRedefine klass"
linktitle: "XmlSchemaRedefine"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaRedefine klass. Representerar redefine‑elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass kan användas för att tillåta enkla och komplexa typer, grupper och attributgrupper från externa schematfiler att omdefinieras i det aktuella schemat. Klassen kan också användas för att tillhandahålla versionering av schematelementen i C++."
type: docs
weight: 5600
url: /sv/cpp/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine class


Representerar **redefine**‑elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass kan användas för att tillåta enkla och komplexa typer, grupper och attributgrupper från externa schematfiler att omdefinieras i det aktuella schemat. Klassen kan också användas för att tillhandahålla versionering av schematelementen.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AttributeGroups](./get_attributegroups/)() | Returnerar [XmlSchemaObjectTable](../xmlschemaobjecttable/) för alla attribut i schemat, som innehåller efterkompileringstolkningen av värdet **AttributeGroups**. |
| [get_Groups](./get_groups/)() | Returnerar [XmlSchemaObjectTable](../xmlschemaobjecttable/) för alla grupper i schemat, som innehåller efterkompileringstolkningen av värdet **Groups**. |
| [get_Items](./get_items/)() | Returnerar samlingen av följande klasser: [XmlSchemaAnnotation](../xmlschemaannotation/), [XmlSchemaAttributeGroup](../xmlschemaattributegroup/), [XmlSchemaComplexType](../xmlschemacomplextype/), [XmlSchemaSimpleType](../xmlschemasimpletype/), och [XmlSchemaGroup](../xmlschemagroup/). |
| [get_SchemaTypes](./get_schematypes/)() | Returnerar [XmlSchemaObjectTable](../xmlschemaobjecttable/) för alla enkla och komplexa typer i schemat, som innehåller efterkompileringstolkningen av värdet **SchemaTypes**. |
| [XmlSchemaRedefine](./xmlschemaredefine/)() | Initierar en ny instans av klassen [XmlSchemaRedefine](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
