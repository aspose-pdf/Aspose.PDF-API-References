---
title: "System::Xml::Schema::XmlSchemaSet::Reprocess метод"
linktitle: "Reprocess"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaSet::Reprocess метод. Повторно обрабатывает XML Schema definition language (XSD) схему, уже существующую в XmlSchemaSet в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess method


Повторно обрабатывает XML [Schema](../../) схему языка определения (XSD), которая уже существует в [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| схема | SharedPtr\<XmlSchema\> | Схема для повторной обработки. |

### ReturnValue

Объект [XmlSchema](../../xmlschema/), если схема является корректной. Если схема недействительна и указан [ValidationEventHandler](../../validationeventhandler/), возвращается **nullptr** и генерируется соответствующее событие проверки. В противном случае бросается [XmlSchemaException](../../xmlschemaexception/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
