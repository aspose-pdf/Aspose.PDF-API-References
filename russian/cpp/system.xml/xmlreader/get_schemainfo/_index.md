---
title: "System::Xml::XmlReader::get_SchemaInfo метод"
linktitle: "get_SchemaInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::get_SchemaInfo метод. Возвращает информацию о схеме, назначенную текущему узлу в результате проверки схемы в C++."
type: docs
weight: 2200
url: /ru/cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Возвращает информацию схемы, присвоенную текущему узлу в результате проверки схемы.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

Объект IXmlSchemaInfo, содержащий информацию о схеме для текущего узла. Информация о [Schema](../../../system.xml.schema/) может быть установлена для элементов, атрибутов или текстовых узлов с ненулевым значением [XmlReader::get_ValueType](../get_valuetype/). Если текущий узел не относится к перечисленным типам узлов, либо экземпляр [XmlReader](../) не предоставляет информацию о схеме, этот метод возвращает **nullptr**. Если этот метод вызывается из объекта [XmlTextReader](../../xmltextreader/) или [XmlValidatingReader](../../xmlvalidatingreader/), он всегда возвращает **nullptr**. Эти реализации [XmlReader](../) не раскрывают информацию о схеме через метод get_SchemaInfo.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
