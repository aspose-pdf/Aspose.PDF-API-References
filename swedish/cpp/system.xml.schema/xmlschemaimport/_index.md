---
title: "System::Xml::Schema::XmlSchemaImport-klass"
linktitle: "XmlSchemaImport"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaImport-klass. Representerar import‑elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass används för att importera schemakomponenter från andra scheman i C++."
type: docs
weight: 3500
url: /sv/cpp/system.xml.schema/xmlschemaimport/
---
## XmlSchemaImport class


Representerar **import**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass används för att importera schemakomponenter från andra scheman.

```cpp
class XmlSchemaImport : public System::Xml::Schema::XmlSchemaExternal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Returnerar **annotation**-värdet. |
| [get_Namespace](./get_namespace/)() | Returnerar mål-namnutrymmet för det importerade schemat som en Uniform Resource Identifier (URI)-referens. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Ställer in **annotation**-värdet. |
| [set_Namespace](./set_namespace/)(const String\&) | Ställer in mål-namnutrymmet för det importerade schemat som en Uniform Resource Identifier (URI)-referens. |
| [XmlSchemaImport](./xmlschemaimport/)() | Initierar en ny instans av klassen [XmlSchemaImport](./). |
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
