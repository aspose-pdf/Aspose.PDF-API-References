---
title: "System::Xml::Schema::XmlSchemaAnnotation-klass"
linktitle: "XmlSchemaAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAnnotation-klass. Representerar World Wide Web Consortium (W3C) **annotation**-elementet i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml.schema/xmlschemaannotation/
---
## XmlSchemaAnnotation class


Representerar World Wide [Web](../../system.web/) Consortium (W3C) **annotation**-elementet.

```cpp
class XmlSchemaAnnotation : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Id](./get_id/)() | Returnerar sträng‑id. |
| [get_Items](./get_items/)() | Returnerar **Items**-samlingen som används för att lagra underordnade elementen **appinfo** och **documentation**. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Returnerar de kvalificerade attributen som inte tillhör schemats mål-namnrymd. |
| [set_Id](./set_id/)(const String\&) | Ställer in sträng‑id. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Anger de kvalificerade attributen som inte tillhör schemats mål-namnrymd. |
| [XmlSchemaAnnotation](./xmlschemaannotation/)() | Initierar en ny instans av klassen [XmlSchemaAnnotation](./). |
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
