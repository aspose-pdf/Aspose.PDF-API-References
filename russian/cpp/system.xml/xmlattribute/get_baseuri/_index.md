---
title: "System::Xml::XmlAttribute::get_BaseURI метод"
linktitle: "get_BaseURI"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttribute::get_BaseURI метод. Возвращает базовый Универсальный Идентификатор Ресурса (URI) узла в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI method


Возвращает базовый Унифицированный идентификатор ресурса (URI) узла.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### ReturnValue

Местоположение, из которого был загружен узел, или [String::Empty](../../../system/string/empty/) если у узла нет базового URI. Узлы [Attribute](../../../system/attribute/) имеют тот же базовый URI, что и их элемент‑владелец. Если у узла атрибута нет элемента‑владельца, get_BaseURI возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Class [String](../../../system/string/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
