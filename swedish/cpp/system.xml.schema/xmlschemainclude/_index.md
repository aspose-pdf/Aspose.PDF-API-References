---
title: "System::Xml::Schema::XmlSchemaInclude klass"
linktitle: "XmlSchemaInclude"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaInclude klass. Representerar include-elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass används för att inkludera deklarationer och definitioner från ett externt schema. De inkluderade deklarationerna och definitionerna blir sedan tillgängliga för bearbetning i det omgivande schemat i C++."
type: docs
weight: 3600
url: /sv/cpp/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude class


Representerar **include**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass används för att inkludera deklarationer och definitioner från ett externt schema. De inkluderade deklarationerna och definitionerna blir sedan tillgängliga för bearbetning i det omgivande schemat.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returnerar **annotation**-värdet. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Ställer in **annotation**-värdet. |
| [XmlSchemaInclude](./xmlschemainclude/)() | Initierar en ny instans av klassen [XmlSchemaInclude](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
