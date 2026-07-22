---
title: "System::Xml::Schema::XmlSchemaComplexContent klass"
linktitle: "XmlSchemaComplexContent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaComplexContent klass. Representerar **complexContent**-elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass representerar den komplexa innehållsmodellen för komplexa typer. Den innehåller utökningar eller begränsningar på en komplex typ som har antingen endast element eller blandat innehåll i C++."
type: docs
weight: 1800
url: /sv/cpp/system.xml.schema/xmlschemacomplexcontent/
---
## XmlSchemaComplexContent class


Representerar **complexContent**-elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass representerar den komplexa innehållsmodellen för komplexa typer. Den innehåller utökningar eller begränsningar på en komplex typ som har antingen endast element eller blandat innehåll.

```cpp
class XmlSchemaComplexContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Content](./get_content/)() override | Returnerar innehållet. |
| [get_IsMixed](./get_ismixed/)() | Returnerar information som avgör om typen har en blandad innehållsmodell. |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Ställer in innehållet. |
| [set_IsMixed](./set_ismixed/)(bool) | Ställer in information som avgör om typen har en blandad innehållsmodell. |
| [XmlSchemaComplexContent](./xmlschemacomplexcontent/)() | Initierar en ny instans av klassen [XmlSchemaComplexContent](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
