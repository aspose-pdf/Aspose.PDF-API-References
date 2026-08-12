---
title: "System::Xml::Schema::XmlSchemaKeyref klass"
linktitle: "XmlSchemaKeyref"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaKeyref klass. Denna klass representerar keyref-elementet från XMLSchema enligt World Wide Web Consortium (W3C) i C++."
type: docs
weight: 4000
url: /sv/cpp/system.xml.schema/xmlschemakeyref/
---
## XmlSchemaKeyref class


Denna klass representerar **keyref**-elementet från XMLSchema enligt World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaKeyref : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Refer](./get_refer/)() | Returnerar namnet på nyckeln som denna begränsning refererar till i en annan enkel eller komplex typ. |
| [set_Refer](./set_refer/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på nyckeln som denna begränning refererar till i en annan enkel eller komplex typ. |
| [XmlSchemaKeyref](./xmlschemakeyref/)() | Initierar en ny instans av klassen [XmlSchemaKeyref](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
