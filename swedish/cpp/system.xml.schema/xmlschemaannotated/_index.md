---
title: "System::Xml::Schema::XmlSchemaAnnotated-klass"
linktitle: "XmlSchemaAnnotated"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAnnotated-klass. Bas‑klassen för alla element som kan innehålla annoteringselement i C++."
type: docs
weight: 600
url: /sv/cpp/system.xml.schema/xmlschemaannotated/
---
## XmlSchemaAnnotated class


Bas‑klassen för alla element som kan innehålla annoteringselement.

```cpp
class XmlSchemaAnnotated : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returnerar **annotation**-egenskapen. |
| [get_Id](./get_id/)() | Returnerar sträng‑id. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör det aktuella schemats mål‑namnutrymme. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Ställer in **annotation**-egenskapen. |
| [set_Id](./set_id/)(const String\&) | Ställer in sträng‑id. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Ställer in de kvalificerade attributen som inte tillhör det aktuella schemats mål‑namnutrymme. |
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
