---
title: "System::Xml::Schema::XmlSchemaSimpleContentExtension‑klass"
linktitle: "XmlSchemaSimpleContentExtension"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSimpleContentExtension‑klass. Representerar extension‑elementet för enkelt innehåll från XML Schema enligt World Wide Web Consortium (W3C). Denna klass kan användas för att härleda enkla typer genom extension. Sådana härledningar används för att utöka det enkla typinnehållet i elementet genom att lägga till attribut i C++."
type: docs
weight: 6000
url: /sv/cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Representerar **extension**‑elementet för enkelt innehåll från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass kan användas för att härleda enkla typer genom extension. Sådana härledningar används för att utöka det enkla typinnehållet i elementet genom att lägga till attribut.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returnerar [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) som ska användas för attributvärdet. |
| [get_Attributes](./get_attributes/)() | Returnerar samlingen av [XmlSchemaAttribute](../xmlschemaattribute/) och [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Returnerar namnet på en inbyggd datatyp eller enkel typ som denna typ är utökad från. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Ställer in [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) som ska användas för attributvärdet. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på en inbyggd datatyp eller enkel typ som denna typ är utökad från. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | Initierar en ny instans av klassen [XmlSchemaSimpleContentExtension](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
