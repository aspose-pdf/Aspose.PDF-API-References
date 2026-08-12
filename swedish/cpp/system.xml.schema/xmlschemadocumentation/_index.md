---
title: "System::Xml::Schema::XmlSchemaDocumentation class"
linktitle: "XmlSchemaDocumentation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaDocumentation class. Representerar dokumentationselementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass specificerar information som ska läsas eller användas av människor inom en annotation i C++."
type: docs
weight: 2500
url: /sv/cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


Representerar **documentation**‑elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass specificerar information som ska läsas eller användas av människor inom en **annotation**.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Language](./get_language/)() | Returnerar attributet **xml:lang**. Detta fungerar som en indikator på språket som används i innehållet. |
| [get_Markup](./get_markup/)() | Returnerar en array av [XmlNode](../../system.xml/xmlnode/)‑objekt som representerar dokumentationsbarnnoderna. |
| [get_Source](./get_source/)() | Returnerar Uniform Resource Identifier (URI)-källan för informationen. |
| [set_Language](./set_language/)(const String\&) | Ställer in attributet **xml:lang**. Detta fungerar som en indikator på språket som används i innehållet. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Ställer in en array av [XmlNode](../../system.xml/xmlnode/)‑objekt som representerar dokumentationsbarnnoderna. |
| [set_Source](./set_source/)(const String\&) | Ställer in Uniform Resource Identifier (URI)-källan för informationen. |
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
