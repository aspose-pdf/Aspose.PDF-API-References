---
title: "System::Xml::Schema::XmlSchemaAttribute klass"
linktitle: "XmlSchemaAttribute"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAttribute-klass. Representerar attribute‑elementet från XML‑schemat enligt World Wide Web Consortium (W3C). Attribut ger ytterligare information för andra dokumentelement. Attribut‑taggen är inbäddad mellan taggarna för ett dokuments element i schemat. XML‑dokumentet visar attribut som namngivna objekt i öppningstaggen för ett element i C++."
type: docs
weight: 1100
url: /sv/cpp/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute class


Representerar **attribute**‑elementet från XML‑[Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Attribut ger ytterligare information för andra dokumentelement. **attribute**‑taggen är inbäddad mellan taggarna för ett dokuments element i schemat. XML‑dokumentet visar attribut som namngivna objekt i öppningstaggen för ett element.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AttributeSchemaType](./get_attributeschematype/)() | Returnerar ett [XmlSchemaSimpleType](../xmlschemasimpletype/)‑objekt som representerar attributets typ baserat på värdet från [XmlSchemaAttribute::get_SchemaType](./get_schematype/) eller [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/). |
| [get_AttributeType](./get_attributetype/)() | Returnerar objektet baserat på värdet från [XmlSchemaAttribute::get_SchemaType](./get_schematype/) eller [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) för attributet som innehåller efterkompileringstolkningen av **AttributeType**‑värdet. |
| [get_DefaultValue](./get_defaultvalue/)() | Returnerar standardvärdet för attributet. |
| [get_FixedValue](./get_fixedvalue/)() | Returnerar det fasta värdet för attributet. |
| [get_Form](./get_form/)() | Returnerar formen för attributet. |
| [get_Name](./get_name/)() | Returnerar namnet på attributet. |
| [get_QualifiedName](./get_qualifiedname/)() | Returnerar det kvalificerade namnet för attributet. |
| [get_RefName](./get_refname/)() | Returnerar namnet på ett attribut som deklarerats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [get_SchemaType](./get_schematype/)() | Returnerar attributtypen till en enkel typ. |
| [get_SchemaTypeName](./get_schematypename/)() | Returnerar namnet på den enkla typen som definierats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [get_Use](./get_use/)() | Returnerar information om hur attributet används. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Ställer in standardvärdet för attributet. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Ställer in det fasta värdet för attributet. |
| [set_Form](./set_form/)(XmlSchemaForm) | Ställer in formen för attributet. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på attributet. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på ett attribut som deklarerats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Ställer in attributtypen till en enkel typ. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på den enkla typen som definierats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [set_Use](./set_use/)(XmlSchemaUse) | Ställer in information om hur attributet används. |
| [XmlSchemaAttribute](./xmlschemaattribute/)() | Initierar en ny instans av klassen [XmlSchemaAttribute](./). |
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
