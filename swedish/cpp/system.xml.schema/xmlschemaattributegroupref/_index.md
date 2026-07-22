---
title: "System::Xml::Schema::XmlSchemaAttributeGroupRef klass"
linktitle: "XmlSchemaAttributeGroupRef"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAttributeGroupRef klass. Representerar **attributeGroup**-elementet med **ref**-attributet från XML Schema enligt specifikationen. AttributesGroupRef är referensen för ett attributeGroup, namn‑egenskapen innehåller den attributgrupp som refereras i C++."
type: docs
weight: 1300
url: /sv/cpp/system.xml.schema/xmlschemaattributegroupref/
---
## XmlSchemaAttributeGroupRef class


Representerar **attributeGroup**-elementet med **ref**-attributet från XML [Schema](../) enligt [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454). AttributesGroupRef är referensen för ett attributeGroup, namn‑egenskapen innehåller den attributgrupp som refereras.

```cpp
class XmlSchemaAttributeGroupRef : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_RefName](./get_refname/)() | Returnerar namnet på det refererade **attributeGroup**-elementet. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på det refererade **attributeGroup**-elementet. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/)() | Initierar en ny instans av klassen [XmlSchemaAttributeGroupRef](./). |
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
