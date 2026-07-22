---
title: "System::Xml::Schema::XmlSchemaComplexContentExtension klass"
linktitle: "XmlSchemaComplexContentExtension"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaComplexContentExtension klass. Representerar extension-elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass är för komplexa typer med komplex innehållsmodell som härleds genom extension. Den utökar den komplexa typen genom att lägga till attribut eller element i C++."
type: docs
weight: 1900
url: /sv/cpp/system.xml.schema/xmlschemacomplexcontentextension/
---
## XmlSchemaComplexContentExtension class


Representerar **extension**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass är för komplexa typer med komplex innehållsmodell som härleds genom extension. Den utökar den komplexa typen genom att lägga till attribut eller element.

```cpp
class XmlSchemaComplexContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returnerar [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten i den komplexa innehållsmodellen. |
| [get_Attributes](./get_attributes/)() | Returnerar samlingen av attribut för det komplexa innehållet. Innehåller [XmlSchemaAttribute](../xmlschemaattribute/) och [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) element. |
| [get_BaseTypeName](./get_basetypename/)() | Returnerar namnet på den komplexa typen som denna typ härleds från genom extension. |
| [get_Particle](./get_particle/)() | Returnerar en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Ställer in [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten i den komplexa innehållsmodellen. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på den komplexa typen som denna typ härleds från genom extension. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Ställer in en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexContentExtension](./xmlschemacomplexcontentextension/)() | Initierar en ny instans av [XmlSchemaComplexContentExtension](./) klass. |
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
