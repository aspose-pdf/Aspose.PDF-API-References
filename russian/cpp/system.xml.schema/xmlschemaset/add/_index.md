---
title: "System::Xml::Schema::XmlSchemaSet::Add метод"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSet::Add метод. Добавляет заданный XmlSchema в XmlSchemaSet в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Добавляет заданный [XmlSchema](../../xmlschema/) в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Объект [XmlSchema](../../xmlschema/) для добавления в [XmlSchemaSet](../). |

### ReturnValue

Объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан [ValidationEventHandler](../../validationeventhandler/), тогда возвращается **nullptr** и генерируется соответствующее событие проверки. В противном случае бросается [XmlSchemaException](../../xmlschemaexception/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Добавляет все XML [Schema](../../) язык определения (XSD) схемы из указанного [XmlSchemaSet](../) в [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | Объект [XmlSchemaSet](../). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Добавляет схему XML [Schema](../../) языка определения (XSD), содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | String | Значение свойства **targetNamespace** схемы, или **nullptr**, чтобы использовать **targetNamespace**, указанный в схеме. |
| schemaDocument | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/). |

### ReturnValue

Объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан [ValidationEventHandler](../../validationeventhandler/), тогда возвращается **nullptr** и генерируется соответствующее событие проверки. В противном случае бросается [XmlSchemaException](../../xmlschemaexception/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Add(String, const String\&) method


Добавляет схему XML [Schema](../../) языка определения (XSD) по указанному URL в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | String | Значение свойства **targetNamespace** схемы, или **nullptr**, чтобы использовать **targetNamespace**, указанный в схеме. |
| schemaUri | const String\& | URL, указывающий схему для загрузки. |

### ReturnValue

Объект [XmlSchema](../../xmlschema/), если схема действительна. Если схема недействительна и указан [ValidationEventHandler](../../validationeventhandler/), тогда возвращается **nullptr** и генерируется соответствующее событие проверки. В противном случае бросается [XmlSchemaException](../../xmlschemaexception/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
