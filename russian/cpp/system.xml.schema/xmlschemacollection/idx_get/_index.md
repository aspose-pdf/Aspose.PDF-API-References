---
title: "System::Xml::Schema::XmlSchemaCollection::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaCollection::idx_get метод. Возвращает XmlSchema, связанный с указанным URI пространства имён, в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get method


Возвращает [XmlSchema](../../xmlschema/), связанный с указанным URI пространства имён.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const String\& | URI пространства имён, связанный со схемой, которую вы хотите вернуть. Обычно это **targetNamespace** схемы. |

### ReturnValue

Связанный [XmlSchema](../../xmlschema/) с URI пространства имён; **nullptr**, если нет загруженной схемы, связанной с указанным пространством имён, или если пространство имён связано со схемой XDR.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
