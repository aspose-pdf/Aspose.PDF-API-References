---
title: "System::Xml::Schema::XmlSchemaComplexContentRestriction klass"
linktitle: "XmlSchemaComplexContentRestriction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaComplexContentRestriction klass. Representerar restriktionselementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass är för komplexa typer med en komplex innehållsmodell som härleds genom restriktion. Den begränsar innehållet i den komplexa typen till en delmängd av den ärvda komplexa typen i C++."
type: docs
weight: 2000
url: /sv/cpp/system.xml.schema/xmlschemacomplexcontentrestriction/
---
## XmlSchemaComplexContentRestriction class


Representerar **restriction**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass är för komplexa typer med en komplex innehållsmodell härledd genom restriction. Den begränsar innehållet i den komplexa typen till en delmängd av den ärvda komplexa typen.

```cpp
class XmlSchemaComplexContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returnerar [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten i den komplexa innehållsmodellen. |
| [get_Attributes](./get_attributes/)() | Returnerar samlingen av attribut för den komplexa typen. Innehåller elementen [XmlSchemaAttribute](../xmlschemaattribute/) och [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Returnerar namnet på en komplex typ som denna typ härleds från genom restriction. |
| [get_Particle](./get_particle/)() | Returnerar en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Ställer in [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten i den komplexa innehållsmodellen. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på en komplex typ som denna typ härleds från genom restriction. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Ställer in en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/)() | Initierar en ny instans av klassen [XmlSchemaComplexContentRestriction](./). |
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
