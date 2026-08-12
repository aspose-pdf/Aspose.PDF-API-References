---
title: "System::Xml::XmlValidatingReader::get_LocalName метод"
linktitle: "get_LocalName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlValidatingReader::get_LocalName метод. Возвращает локальное имя текущего узла в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName method


Возвращает локальное имя текущего узла.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### ReturnValue

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, которые не имеют имени (например, **[Text](../../../system.text/)**, **Comment** и т.д.), этот метод возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
