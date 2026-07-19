---
title: "System::Xml::Schema::XmlSchemaCollection::Contains метод"
linktitle: "Contains"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaCollection::Contains метод. Возвращает значение, указывающее, находится ли targetNamespace указанного XmlSchema в коллекции, в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Возвращает значение, указывающее, находится ли **targetNamespace** указанного [XmlSchema](../../xmlschema/) в коллекции.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Объект [XmlSchema](../../xmlschema/). |

### ReturnValue

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaCollection::Contains(const String\&) method


Возвращает значение, указывающее, находится ли схема с указанным пространством имён в коллекции.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const String\& | URI пространства имён, связанный со схемой. Для XML‑схем обычно это целевое пространство имён. |

### ReturnValue

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
