---
title: "System::Xml::XmlNamespaceManager::LookupNamespace method"
linktitle: "LookupNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamespaceManager::LookupNamespace method. Возвращает URI пространства имён для указанного префикса в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace method


Возвращает URI пространства имён для указанного префикса.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const String\& | Префикс, URI пространства имён которого вы хотите разрешить. Чтобы соответствовать пространству имён по умолчанию, передайте [String::Empty](../../../system/string/empty/). |

### ReturnValue

URI пространства имён для **prefix** или **nullptr**, если соответствующее пространство имён не найдено. Возвращаемая строка атомизирована. Для получения дополнительной информации об атомизированных строках см. класс [XmlNameTable](../../xmlnametable/).

## См. также

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
