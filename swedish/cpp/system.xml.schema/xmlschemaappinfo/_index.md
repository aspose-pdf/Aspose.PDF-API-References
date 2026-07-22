---
title: "System::Xml::Schema::XmlSchemaAppInfo class"
linktitle: "XmlSchemaAppInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaAppInfo class. Representerar World Wide Web Consortium (W3C) appinfo-elementet i C++."
type: docs
weight: 1000
url: /sv/cpp/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo class


Representerar World Wide [Web](../../system.web/) Consortium (W3C) **appinfo**-elementet.

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Markup](./get_markup/)() | Returnerar en array av [XmlNode](../../system.xml/xmlnode/)‑objekt som representerar **appinfo**‑barnnoderna. |
| [get_Source](./get_source/)() | Returnerar källan till applikationsinformationen. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Ställer in en array av [XmlNode](../../system.xml/xmlnode/)‑objekt som representerar **appinfo**‑barnnoderna. |
| [set_Source](./set_source/)(const String\&) | Ställer in källan till applikationsinformationen. |
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
