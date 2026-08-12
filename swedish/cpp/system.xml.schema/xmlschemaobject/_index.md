---
title: "System::Xml::Schema::XmlSchemaObject klass"
linktitle: "XmlSchemaObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaObject klass. Representerar rotklassen för Xml‑schemamodellhierarkin och fungerar som en basklass för klasser såsom XmlSchema‑klassen i C++."
type: docs
weight: 5000
url: /sv/cpp/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject class


Representerar rotklassen för [Xml](../../system.xml/) schemamodellhierarkin och fungerar som en basklass för klasser såsom [XmlSchema](../xmlschema/) klass.

```cpp
class XmlSchemaObject : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_LineNumber](./get_linenumber/)() | Returnerar radnumret i filen som **schema**-elementet refererar till. |
| [get_LinePosition](./get_lineposition/)() | Returnerar radpositionen i filen som **schema**-elementet refererar till. |
| [get_Namespaces](./get_namespaces/)() | Returnerar XmlSerializerNamespaces att använda med detta schemaobjekt. |
| [get_Parent](./get_parent/)() | Returnerar föräldern till detta [XmlSchemaObject](./). |
| [get_SourceUri](./get_sourceuri/)() | Returnerar källplatsen för filen som laddade schemat. |
| [set_LineNumber](./set_linenumber/)(int32_t) | Ställer in radnumret i filen som **schema**-elementet refererar till. |
| [set_LinePosition](./set_lineposition/)(int32_t) | Ställer in radpositionen i filen som **schema**-elementet refererar till. |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Ställer in XmlSerializerNamespaces att använda med detta schemaobjekt. |
| [set_Parent](./set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Sätter föräldern till detta [XmlSchemaObject](./). |
| [set_SourceUri](./set_sourceuri/)(const String\&) | Ställer in källplatsen för filen som laddade schemat. |
| [XmlSchemaObject](./xmlschemaobject/)() | Initierar en ny instans av [XmlSchemaObject](./) klass. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
