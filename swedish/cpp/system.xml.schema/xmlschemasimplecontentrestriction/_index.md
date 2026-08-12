---
title: "System::Xml::Schema::XmlSchemaSimpleContentRestriction klass"
linktitle: "XmlSchemaSimpleContentRestriction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSimpleContentRestriction-klass. Representerar restriktions-elementet för enkelt innehåll från XML Schema enligt World Wide Web Consortium (W3C). Denna klass kan användas för att härleda enkla typer genom restriktion. Sådana härledningar kan användas för att begränsa värdeintervallet för elementet till en delmängd av de värden som anges i den ärvda enkla typen i C++."
type: docs
weight: 6100
url: /sv/cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


Representerar **restriction**-elementet för enkelt innehåll från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass kan användas för att härleda enkla typer genom restriktion. Sådana härledningar kan användas för att begränsa värdeintervallet för elementet till en delmängd av de värden som anges i den ärvda enkla typen.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returnerar ett [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) som ska användas för attributvärdet. |
| [get_Attributes](./get_attributes/)() | Returnerar [XmlSchemaAttribute](../xmlschemaattribute/) och [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/)-samlingen av attribut för den enkla typen. |
| [get_BaseType](./get_basetype/)() | Returnerar det enkla typens grundvärde. |
| [get_BaseTypeName](./get_basetypename/)() | Returnerar namnet på den inbyggda datatypen eller enkla typen som denna typ är härledd från. |
| [get_Facets](./get_facets/)() | Returnerar ett [Xml](../../system.xml/)[Schema](../)-facet. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Ställer in ett [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) som ska användas för attributvärdet. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Ställer in det enkla typens basvärde. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på den inbyggda datatypen eller enkla typen som denna typ härstammar från. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | Initierar en ny instans av klassen [XmlSchemaSimpleContentRestriction](./). |
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
