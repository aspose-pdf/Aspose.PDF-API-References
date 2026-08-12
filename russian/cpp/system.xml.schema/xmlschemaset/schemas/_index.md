---
title: "System::Xml::Schema::XmlSchemaSet::Schemas метод"
linktitle: "Схемы"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSet::Schemas метод. Возвращает коллекцию всех XML Schema definition language (XSD) схем в XmlSchemaSet в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


Возвращает коллекцию всех XML [Schema](../../) definition language (XSD) схем в [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### ReturnValue

Объект IList, содержащий все схемы, добавленные в [XmlSchemaSet](../). Если в [XmlSchemaSet](../) не добавлено схем, возвращается пустая коллекция.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Schemas(String) method


Возвращает коллекцию всех XML [Schema](../../) definition language (XSD) схем в [XmlSchemaSet](../), принадлежащих заданному пространству имён.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| targetNamespace | String | Свойство схемы **targetNamespace**. |

### ReturnValue

Объект IList, содержащий все схемы, добавленные в [XmlSchemaSet](../) и принадлежащие заданному пространству имён. Если в [XmlSchemaSet](../) не добавлено схем, возвращается пустая коллекция.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
