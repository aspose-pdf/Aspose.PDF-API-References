---
title: "System::Xml::IXmlNamespaceResolver::GetNamespacesInScope метод"
linktitle: "GetNamespacesInScope"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::IXmlNamespaceResolver::GetNamespacesInScope метод. Возвращает коллекцию определённых сопоставлений префикс‑пространство имён, которые в данный момент находятся в области видимости в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope method


Возвращает коллекцию определённых сопоставлений префикс‑пространство имён, которые в данный момент находятся в области видимости.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | XmlNamespaceScope | Значение [XmlNamespaceScope](../../xmlnamespacescope/), которое указывает тип возвращаемых узлов пространства имён. |

### ReturnValue

Коллекция IDictionary, содержащая текущие пространства имён в области видимости.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
