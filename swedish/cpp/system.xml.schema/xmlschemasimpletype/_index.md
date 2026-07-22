---
title: "System::Xml::Schema::XmlSchemaSimpleType-klass"
linktitle: "XmlSchemaSimpleType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSimpleType-klass. Representerar simpleType-elementet för enkelt innehåll från XML Schema enligt World Wide Web Consortium (W3C). Denna klass definierar en enkel typ. Enkla typer kan ange information och begränsningar för värdet av attribut eller element med enbart textinnehåll i C++."
type: docs
weight: 6200
url: /sv/cpp/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType class


Representerar **simpleType**-elementet för enkelt innehåll från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass definierar en enkel typ. Enkla typer kan ange information och begränsningar för värdet av attribut eller element med enbart textinnehåll.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Content](./get_content/)() | Returnerar en av [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/), eller [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [set_Content](./set_content/)(const SharedPtr\<XmlSchemaSimpleTypeContent\>\&) | Ställer in en av [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/), eller [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [XmlSchemaSimpleType](./xmlschemasimpletype/)() | Initierar en ny instans av klassen [XmlSchemaSimpleType](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
