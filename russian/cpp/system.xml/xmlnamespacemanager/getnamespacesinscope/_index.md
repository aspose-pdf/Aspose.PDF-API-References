---
title: "System::Xml::XmlNamespaceManager::GetNamespacesInScope метод"
linktitle: "GetNamespacesInScope"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamespaceManager::GetNamespacesInScope метод. Возвращает коллекцию имён пространств имён, ключом которой является префикс, которую можно использовать для перечисления текущих областей пространств имён в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope method


Возвращает коллекцию имён пространств имён, ключом которой является префикс, которую можно использовать для перечисления текущих пространств имён в области видимости.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| область | XmlNamespaceScope | Значение перечисления, указывающее тип узлов пространства имён, которые следует вернуть. |

### ReturnValue

Коллекция пар пространство имён‑префикс, находящихся в текущей области.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
