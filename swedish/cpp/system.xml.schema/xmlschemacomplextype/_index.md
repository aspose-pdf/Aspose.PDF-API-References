---
title: "System::Xml::Schema::XmlSchemaComplexType-klass"
linktitle: "XmlSchemaComplexType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaComplexType-klass. Representerar complexType-elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass definierar en komplex typ som bestämmer uppsättningen av attribut och innehåll för ett element i C++."
type: docs
weight: 2100
url: /sv/cpp/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType class


Representerar elementet **complexType** från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass definierar en komplex typ som bestämmer uppsättningen av attribut och innehåll för ett element.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Returnerar värdet för komponenten [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) i den komplexa typen. |
| [get_Attributes](./get_attributes/)() | Returnerar samlingen av attribut för den komplexa typen. |
| [get_AttributeUses](./get_attributeuses/)() | Returnerar samlingen av alla de sammanställda attribut för denna komplexa typ och dess bastyper. |
| [get_AttributeWildcard](./get_attributewildcard/)() | Returnerar post‑kompilationsvärdet för **anyAttribute** för denna komplexa typ och dess bastyp(er). |
| [get_Block](./get_block/)() | Returnerar **block**-attributet. |
| [get_BlockResolved](./get_blockresolved/)() | Returnerar värdet efter att typen har kompilerats till post‑schemavaliderings‑informationsuppsättningen (infoset). Detta värde indikerar hur typen verkställs när **xsi:type** används i instansdokumentet. |
| [get_ContentModel](./get_contentmodel/)() | Returnerar post‑kompilations‑[XmlSchemaContentModel](../xmlschemacontentmodel/) för denna komplexa typ. |
| [get_ContentType](./get_contenttype/)() | Returnerar innehållsmodellen för den komplexa typen som innehåller post‑kompilationsvärdet. |
| [get_ContentTypeParticle](./get_contenttypeparticle/)() | Returnerar partikeln som innehåller post‑kompilationsvärdet för [XmlSchemaComplexType::get_ContentType](./get_contenttype/)-partikeln. |
| [get_IsAbstract](./get_isabstract/)() | Returnerar informationen som avgör om **complexType**‑elementet kan användas i instansdokumentet. |
| [get_IsMixed](./get_ismixed/)() override | Returnerar information som avgör om den komplexa typen har en blandad innehållsmodell (markup inom innehållet). |
| [get_Particle](./get_particle/)() | Returnerar kompositortypen som en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Ställer in värdet för [XmlSchemaAnyAttribute](../xmlschemaanyattribute/)-komponenten i den komplexa typen. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Ställer in **block**‑attributet. |
| [set_ContentModel](./set_contentmodel/)(const SharedPtr\<XmlSchemaContentModel\>\&) | Ställer in post‑kompilations‑[XmlSchemaContentModel](../xmlschemacontentmodel/) för denna komplexa typ. |
| [set_IsAbstract](./set_isabstract/)(bool) | Ställer in informationen som avgör om **complexType**‑elementet kan användas i instansdokumentet. |
| [set_IsMixed](./set_ismixed/)(bool) override | Ställer in information som avgör om den komplexa typen har en blandad innehållsmodell (markup inom innehållet). |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Ställer in kompositortypen som en av klasserna [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) eller [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexType](./xmlschemacomplextype/)() | Initierar en ny instans av klassen [XmlSchemaComplexType](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
