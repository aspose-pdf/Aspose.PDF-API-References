---
title: "System::Xml::Schema::XmlSchemaSet::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSet::Add metod. Lägger till det angivna XmlSchema till XmlSchemaSet i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Lägger till det angivna [XmlSchema](../../xmlschema/) till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Det [XmlSchema](../../xmlschema/) objektet som ska läggas till i [XmlSchemaSet](../). |

### ReturnValue

Ett [XmlSchema](../../xmlschema/)‑objekt om schemat är giltigt. Om schemat inte är giltigt och en [ValidationEventHandler](../../validationeventhandler/) har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett [XmlSchemaException](../../xmlschemaexception/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Lägger till alla XML [Schema](../../) definition language (XSD)-scheman i den angivna [XmlSchemaSet](../) till [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | Objektet [XmlSchemaSet](../). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Lägger till XML [Schema](../../) definition language (XSD)-schemat som finns i [XmlReader](../../../system.xml/xmlreader/) till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | String | Schemat **targetNamespace**‑värde, eller **nullptr** för att använda det **targetNamespace** som anges i schemat. |
| schemaDocument | const SharedPtr\<XmlReader\>\& | Objektet [XmlReader](../../../system.xml/xmlreader/). |

### ReturnValue

Ett [XmlSchema](../../xmlschema/)‑objekt om schemat är giltigt. Om schemat inte är giltigt och en [ValidationEventHandler](../../validationeventhandler/) har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett [XmlSchemaException](../../xmlschemaexception/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const String\&) method


Lägger till XML [Schema](../../) definition language (XSD)-schemat på den angivna URL:en till [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | String | Schemat **targetNamespace**‑värde, eller **nullptr** för att använda det **targetNamespace** som anges i schemat. |
| schemaUri | const String\& | URL:en som specificerar schemat att läsa in. |

### ReturnValue

Ett [XmlSchema](../../xmlschema/)‑objekt om schemat är giltigt. Om schemat inte är giltigt och en [ValidationEventHandler](../../validationeventhandler/) har angetts, returneras **nullptr** och den lämpliga valideringshändelsen utlöses. Annars kastas ett [XmlSchemaException](../../xmlschemaexception/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
