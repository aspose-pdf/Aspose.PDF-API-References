---
title: "System::Xml::Schema::XmlSchemaIdentityConstraint klass"
linktitle: "XmlSchemaIdentityConstraint"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaIdentityConstraint klass. Klass för identitetsbegränsningarna: key, keyref och unique-element i C++."
type: docs
weight: 3400
url: /sv/cpp/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint class


Klass för identitetsbegränsningarna: **key**, **keyref** och **unique**-elementen.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Fields](./get_fields/)() | Returnerar samlingen av fält som gäller som barn för XML Path Language ([XPath](../../system.xml.xpath/))-uttrycksselektorn. |
| [get_Name](./get_name/)() | Returnerar namnet på identitetsbegränsningen. |
| [get_QualifiedName](./get_qualifiedname/)() | Returnerar det kvalificerade namnet på identitetsbegränsningen, som innehåller efterkompileringstolkningen av värdet **QualifiedName**. |
| [get_Selector](./get_selector/)() | Returnerar elementet **selector** för [XPath](../../system.xml.xpath/)-uttrycket. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på identitetsbegränsningen. |
| [set_Selector](./set_selector/)(const SharedPtr\<XmlSchemaXPath\>\&) | Ställer in elementet **selector** för [XPath](../../system.xml.xpath/)-uttrycket. |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | Initierar en ny instans av klassen [XmlSchemaIdentityConstraint](./). |
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
