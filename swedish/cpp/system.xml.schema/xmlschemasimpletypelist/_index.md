---
title: "System::Xml::Schema::XmlSchemaSimpleTypeList class"
linktitle: "XmlSchemaSimpleTypeList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSimpleTypeList class. Representerar list‑elementet från XML Schema enligt World Wide Web Consortium (W3C). Denna klass kan användas för att definiera ett simpleType‑element som en lista av värden av en specificerad datatyp i C++."
type: docs
weight: 6400
url: /sv/cpp/system.xml.schema/xmlschemasimpletypelist/
---
## XmlSchemaSimpleTypeList class


Representerar **list**‑elementet från XML [Schema](../) enligt World Wide [Web](../../system.web/) Consortium (W3C). Denna klass kan användas för att definiera ett **simpleType**‑element som en lista av värden av en specificerad datatyp.

```cpp
class XmlSchemaSimpleTypeList : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BaseItemType](./get_baseitemtype/)() | Returnerar [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar typen av **simpleType**‑elementet baserat på [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) och [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) värdena för den enkla typen. |
| [get_ItemType](./get_itemtype/)() | Returnerar **simpleType**‑elementet som härstammar från den typ som anges av basvärdet. |
| [get_ItemTypeName](./get_itemtypename/)() | Returnerar namnet på en inbyggd datatyp eller **simpleType**‑element som definierats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [set_BaseItemType](./set_baseitemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Ställer in [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar typen av **simpleType**‑elementet baserat på [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) och [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) värdena för den enkla typen. |
| [set_ItemType](./set_itemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Ställer in **simpleType**‑elementet som härstammar från den typ som anges av basvärdet. |
| [set_ItemTypeName](./set_itemtypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Ställer in namnet på en inbyggd datatyp eller **simpleType**‑element som definierats i detta schema (eller ett annat schema som anges av den specificerade namnrymden). |
| [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/)() | Initierar en ny instans av klassen [XmlSchemaSimpleTypeList](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
