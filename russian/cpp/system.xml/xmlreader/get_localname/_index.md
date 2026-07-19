---
title: "System::Xml::XmlReader::get_LocalName метод"
linktitle: "get_LocalName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::get_LocalName метод. При переопределении в производном классе получает локальное имя текущего узла в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName method


При переопределении в производном классе возвращает локальное имя текущего узла.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### ReturnValue

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, которые не имеют имени (например, **[Text](../../../system.text/)**, **Comment** и т.д.), этот метод возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
