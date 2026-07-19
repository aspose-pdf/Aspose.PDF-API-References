---
title: "System::Xml::Schema::XmlSchemaSet::Remove метод"
linktitle: "Remove"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSet::Remove метод. Удаляет указанный XML Schema definition language (XSD) схему из XmlSchemaSet в C++."
type: docs
weight: 1300
url: /ru/cpp/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove method


Удаляет указанную XML [Schema](../../) definition language (XSD) схему из [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Объект [XmlSchema](../../xmlschema/) для удаления из [XmlSchemaSet](../). |

### ReturnValue

Объект [XmlSchema](../../xmlschema/) удалён из [XmlSchemaSet](../) или **nullptr**, если схема не найдена в [XmlSchemaSet](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
