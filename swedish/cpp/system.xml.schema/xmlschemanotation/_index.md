---
title: "System::Xml::Schema::XmlSchemaNotation klass"
linktitle: "XmlSchemaNotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaNotation klass. Representerar notationselementet från XML Schema enligt World Wide Web Consortium (W3C). En XML Schemanotation-deklaration är en återuppbyggnad av XML 1.0 NOTATION-deklarationer. Syftet med notationer är att beskriva formatet för icke-XML-data inom ett XML-dokument i C++."
type: docs
weight: 4800
url: /sv/cpp/system.xml.schema/xmlschemanotation/
---
## XmlSchemaNotation class


Representerar **notation**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). En XML [Schema](../)**notation**-deklaration är en återuppbyggnad av **XML** 1.0 NOTATION-deklarationer. Syftet med notationer är att beskriva formatet för icke-XML-data inom ett XML-dokument.

```cpp
class XmlSchemaNotation : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Name](./get_name/)() | Returnerar namnet på notation. |
| [get_Public](./get_public/)() | Returnerar den **public** identifieraren. |
| [get_System](./get_system/)() | Returnerar den **system** identifieraren. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på notation. |
| [set_Public](./set_public/)(const String\&) | Ställer in den **public** identifieraren. |
| [set_System](./set_system/)(const String\&) | Ställer in den **system** identifieraren. |
| [XmlSchemaNotation](./xmlschemanotation/)() | Initierar en ny instans av klassen [XmlSchemaNotation](./). |
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
