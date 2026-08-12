---
title: "System::Xml::Schema::XmlSchemaGroupRef klass"
linktitle: "XmlSchemaGroupRef"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaGroupRef klass. Representerar **group**-elementet med **ref**-attributet från XML‑schemat enligt World Wide Web Consortium (W3C). Denna klass används inom komplexa typer som refererar till en **group** definierad på **schema**-nivå i C++."
type: docs
weight: 3300
url: /sv/cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


Representerar **group**-elementet med **ref**-attributet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass används inom komplexa typer som refererar till en **group** definierad på **schema**-nivå.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Particle](./get_particle/)() | Returnerar en av klasserna [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/), som innehåller post‑kompileringstolkningen av värdet **Particle**. |
| [get_RefName](./get_refname/)() | Returnerar namnet på en grupp definierad i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Anger namnet på en grupp definierad i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Initierar en ny instans av klassen [XmlSchemaGroupRef](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
