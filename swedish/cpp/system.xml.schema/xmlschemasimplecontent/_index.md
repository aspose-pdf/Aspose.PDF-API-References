---
title: "System::Xml::Schema::XmlSchemaSimpleContent-klass"
linktitle: "XmlSchemaSimpleContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSimpleContent-klass. Representerar simpleContent-elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass är för enkla och komplexa typer med enkel innehållsmodell i C++."
type: docs
weight: 5900
url: /sv/cpp/system.xml.schema/xmlschemasimplecontent/
---
## XmlSchemaSimpleContent class


Representerar **simpleContent**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass är för enkla och komplexa typer med enkel innehållsmodell.

```cpp
class XmlSchemaSimpleContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Content](./get_content/)() override | Returnerar en av [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) eller [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Returnerar en av [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) eller [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
