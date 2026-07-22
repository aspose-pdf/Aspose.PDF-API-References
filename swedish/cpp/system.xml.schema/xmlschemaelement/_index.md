---
title: "System::Xml::Schema::XmlSchemaElement klass"
linktitle: "XmlSchemaElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaElement-klass. Representerar element‑elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass är basklassen för alla partikeltyper och används för att beskriva ett element i ett XML‑dokument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement class


Representerar **element**‑elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass är basklassen för alla partikeltyper och används för att beskriva ett element i ett XML‑dokument.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Block](./get_block/)() | Returnerar en **Block**‑derivering. |
| [get_BlockResolved](./get_blockresolved/)() | Returnerar efterkompileringstolkningen av värdet **Block**. |
| [get_Constraints](./get_constraints/)() | Returnerar samlingen av begränsningar för elementet. |
| [get_DefaultValue](./get_defaultvalue/)() | Returnerar standardvärdet för elementet om dess innehåll är en enkel typ eller om elementets innehåll är **textOnly**. |
| [get_ElementSchemaType](./get_elementschematype/)() | Returnerar ett [XmlSchemaType](../xmlschematype/)‑objekt som representerar elementets typ baserat på värdena [XmlSchemaElement::get_SchemaType](./get_schematype/) eller [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) för elementet. |
| [get_ElementType](./get_elementtype/)() | Returnerar ett objekt baserat på [XmlSchemaElement](./) eller [XmlSchemaElement](./) för elementet, som innehåller efterkompileringstolkningen av värdet **ElementType**. |
| [get_Final](./get_final/)() | Returnerar värdet **Final** för att indikera att inga ytterligare derivationer är tillåtna. |
| [get_FinalResolved](./get_finalresolved/)() | Returnerar efterkompileringstolkningen av värdet **Final**. |
| [get_FixedValue](./get_fixedvalue/)() | Returnerar det fasta värdet. |
| [get_Form](./get_form/)() | Returnerar formen för elementet. |
| [get_IsAbstract](./get_isabstract/)() | Returnerar information som indikerar om elementet kan användas i ett instansdokument. |
| [get_IsNillable](./get_isnillable/)() | Returnerar information som visar om **xsi:nil** kan förekomma i instansdata. Anger om ett explicit nil‑värde kan tilldelas elementet. |
| [get_Name](./get_name/)() | Returnerar elementets namn. |
| [get_QualifiedName](./get_qualifiedname/)() | Returnerar det faktiska kvalificerade namnet för det angivna elementet. |
| [get_RefName](./get_refname/)() | Returnerar referensnamnet för ett element som deklarerats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [get_SchemaType](./get_schematype/)() | Returnerar elementets typ. Detta kan vara antingen en komplex typ eller en enkel typ. |
| [get_SchemaTypeName](./get_schematypename/)() | Returnerar namnet på en inbyggd datatyp som definierats i detta schema eller ett annat schema som anges av den specificerade namnrymden. |
| [get_SubstitutionGroup](./get_substitutiongroup/)() | Returnerar namnet på ett element som ersätts av detta element. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Ställer in en **Block**‑derivering. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Ställer in standardvärdet för elementet om dess innehåll är en enkel typ eller om elementets innehåll är **textOnly**. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Ställer in värdet **Final** för att indikera att inga ytterligare derivationer är tillåtna. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Ställer in det fasta värdet. |
| [set_Form](./set_form/)(XmlSchemaForm) | Ställer in formen för elementet. |
| [set_IsAbstract](./set_isabstract/)(bool) | Ställer in information för att ange om elementet kan användas i ett instansdokument. |
| [set_IsNillable](./set_isnillable/)(bool) | Ställer in information som visar om **xsi:nil** kan förekomma i instansdata. Anger om ett explicit nil‑värde kan tilldelas elementet. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på elementet. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in referensnamnet för ett element som deklarerats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Ställer in typen för elementet. Detta kan antingen vara en komplex typ eller en enkel typ. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på en inbyggd datatyp som definierats i detta schema eller ett annat schema som anges av den specificerade namnrymden. |
| [set_SubstitutionGroup](./set_substitutiongroup/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på ett element som ersätts av detta element. |
| [XmlSchemaElement](./xmlschemaelement/)() | Initierar en ny instans av klassen [XmlSchemaElement](./). |
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
