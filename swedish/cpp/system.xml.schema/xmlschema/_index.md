---
title: "System::Xml::Schema::XmlSchema-klass"
linktitle: "XmlSchema"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchema-klass. En minnesrepresentation av ett XML-schema, enligt World Wide Web Consortium (W3C) och i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.schema/xmlschema/
---
## XmlSchema class


En minnesrepresentation av ett XML [Schema](../), enligt World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) och [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Compile](./compile/)(ValidationEventHandler) | Kompilerar XML [Schema](../)[Object](../../system/object/) Modellen (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i den programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering. |
| [Compile](./compile/)(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) | Kompilerar XML [Schema](../)[Object](../../system/object/) Modellen (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i den programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering. |
| [get_AttributeFormDefault](./get_attributeformdefault/)() | Returnerar formen för attribut som deklarerats i schemats mål‑namnrymd. |
| [get_AttributeGroups](./get_attributegroups/)() | Returnerar post‑schemakompileringsvärdet för alla globala attributgrupper i schemat. |
| [get_Attributes](./get_attributes/)() | Returnerar post‑schemakompileringsvärdet för alla attribut i schemat. |
| [get_BlockDefault](./get_blockdefault/)() | Returnerar attributet **blockDefault** som anger standardvärdet för attributet **block** på element och komplexa typer i **targetNamespace** i schemat. |
| [get_ElementFormDefault](./get_elementformdefault/)() | Returnerar formen för element som deklarerats i schemats mål‑namnrymd. |
| [get_Elements](./get_elements/)() | Returnerar post‑schemakompileringsvärdet för alla element i schemat. |
| [get_FinalDefault](./get_finaldefault/)() | Returnerar attributet **finalDefault** som anger standardvärdet för attributet **final** på element och komplexa typer i schemats mål‑namnrymd. |
| [get_Groups](./get_groups/)() | Returnerar post‑schemakompileringsvärdet för alla grupper i schemat. |
| [get_Id](./get_id/)() | Returnerar sträng‑ID:t. |
| [get_Includes](./get_includes/)() | Returnerar samlingen av inkluderade och importerade scheman. |
| [get_IsCompiled](./get_iscompiled/)() | Indikerar om schemat har kompilerats. |
| [get_Items](./get_items/)() | Returnerar samlingen av schemaelement i schemat och används för att lägga till nya elementtyper på **schema**-elementnivå. |
| [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet refererar till. |
| [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet refererar till. |
| [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Returnerar XmlSerializerNamespaces att använda med detta schemaobjekt. |
| [get_Notations](./get_notations/)() | Returnerar post‑schemakompileringsvärdet för alla notationer i schemat. |
| [get_Parent](../xmlschemaobject/get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [get_SchemaTypes](./get_schematypes/)() | Returnerar post‑schemakompileringsvärdet för alla schematyper i schemat. |
| [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [get_TargetNamespace](./get_targetnamespace/)() | Returnerar Uniform Resource Identifier (URI) för schemats mål‑namnrymd. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör schemats mål‑namnrymd. |
| [get_Version](./get_version/)() | Returnerar versionen av schemat. |
| static [Read](./read/)(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) | Läser ett XML-[Schema](../) från den angivna [IO::TextReader](../../system.io/textreader/). |
| static [Read](./read/)(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) | Läser ett XML-[Schema](../) från den angivna strömmen. |
| static [Read](./read/)(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) | Läser ett XML-[Schema](../) från den angivna [XmlReader](../../system.xml/xmlreader/). |
| [set_AttributeFormDefault](./set_attributeformdefault/)(XmlSchemaForm) | Ställer in formen för attribut som deklarerats i schemats mål‑namnrymd. |
| [set_BlockDefault](./set_blockdefault/)(XmlSchemaDerivationMethod) | Ställer in attributet **blockDefault** som sätter standardvärdet för attributet **block** på element och komplexa typer i **targetNamespace** för schemat. |
| [set_ElementFormDefault](./set_elementformdefault/)(XmlSchemaForm) | Ställer in formen för element som deklarerats i schemats mål‑namnrymd. |
| [set_FinalDefault](./set_finaldefault/)(XmlSchemaDerivationMethod) | Ställer in attributet **finalDefault** som sätter standardvärdet för attributet **final** på element och komplexa typer i mål‑namnrymden för schemat. |
| [set_Id](./set_id/)(const String\&) | Ställer in sträng‑ID. |
| [set_LineNumber](../xmlschemaobject/set_linenumber/)(int32_t) | Ställer in radnumret i filen som **schema**-elementet refererar till. |
| [set_LinePosition](../xmlschemaobject/set_lineposition/)(int32_t) | Ställer in radpositionen i filen som **schema**-elementet refererar till. |
| [set_Namespaces](../xmlschemaobject/set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Ställer in XmlSerializerNamespaces att använda med detta schemaobjekt. |
| [set_Parent](../xmlschemaobject/set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Ställer in föräldern till detta [XmlSchemaObject](../xmlschemaobject/). |
| [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const String\&) | Ställer in källplatsen för filen som laddade schemat. |
| [set_TargetNamespace](./set_targetnamespace/)(const String\&) | Ställer in Uniform Resource Identifier (URI) för schemats mål‑namnrymd. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Ställer in de kvalificerade attributen som inte tillhör schemats mål‑namnrymd. |
| [set_Version](./set_version/)(const String\&) | Ställer in versionen av schemat. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&) | Skriver XML [Schema](../) till den angivna datastreamen. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Skriver XML [Schema](../) till den angivna Stream med den angivna [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/). |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&) | Skriver XML [Schema](../) till den angivna [IO::TextWriter](../../system.io/textwriter/). |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Skriver XML [Schema](../) till den angivna TextWriter. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&) | Skriver XML [Schema](../) till den angivna [XmlWriter](../../system.xml/xmlwriter/). |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Skriver XML [Schema](../) till den angivna [XmlWriter](../../system.xml/xmlwriter/). |
| [XmlSchema](./xmlschema/)() | Initierar en ny instans av klassen [XmlSchema](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Initierar en ny instans av klassen [XmlSchemaObject](../xmlschemaobject/). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | XML‑schemats instansnamnrymd. Detta fält är konstant. |
| static [Namespace](./namespace/) | XML‑schemats namnrymd. Detta fält är konstant. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
