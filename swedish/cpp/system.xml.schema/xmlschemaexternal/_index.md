---
title: "System::Xml::Schema::XmlSchemaExternal-klass"
linktitle: "XmlSchemaExternal"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaExternal-klass. Tillhandahåller information om det inkluderade schemat i C++."
type: docs
weight: 2800
url: /sv/cpp/system.xml.schema/xmlschemaexternal/
---
## XmlSchemaExternal class


Tillhandahåller information om det inkluderade schemat.

```cpp
class XmlSchemaExternal : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Id](./get_id/)() | Returnerar sträng‑id. |
| [get_Schema](./get_schema/)() | Returnerar [XmlSchema](../xmlschema/) för det refererade schemat. |
| [get_SchemaLocation](./get_schemalocation/)() | Returnerar Uniform Resource Identifier (URI)-platsen för schemat, vilket talar om för schemaprocessorn var schemat fysiskt finns. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returnerar de kvalificerade attributen, som inte tillhör schemets mål‑namnutrymme. |
| [set_Id](./set_id/)(const String\&) | Ställer in sträng‑id. |
| [set_Schema](./set_schema/)(const SharedPtr\<XmlSchema\>\&) | Ställer in [XmlSchema](../xmlschema/) för det refererade schemat. |
| [set_SchemaLocation](./set_schemalocation/)(const String\&) | Ställer in Uniform Resource Identifier (URI)-platsen för schemat, vilket talar om för schemaprocessorn var schemat fysiskt finns. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Ställer in de kvalificerade attributen, som inte tillhör schemets mål‑namnutrymme. |
| [XmlSchemaExternal](./xmlschemaexternal/)() | Initierar en ny instans av klassen [XmlSchemaExternal](./). |
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
