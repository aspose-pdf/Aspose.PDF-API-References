---
title: "System::Xml::XmlNamespaceManager::LookupPrefix method"
linktitle: "LookupPrefix"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamespaceManager::LookupPrefix method. Находит префикс, объявленный для указанного URI пространства имён в C++."
type: docs
weight: 900
url: /ru/cpp/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix method


Находит префикс, объявленный для указанного URI пространства имён.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const String\& | Пространство имён, которое нужно разрешить для префикса. |

### ReturnValue

Соответствующий префикс. Если сопоставленный префикс отсутствует, метод возвращает [String::Empty](../../../system/string/empty/). Если передано значение null, возвращается **nullptr**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
