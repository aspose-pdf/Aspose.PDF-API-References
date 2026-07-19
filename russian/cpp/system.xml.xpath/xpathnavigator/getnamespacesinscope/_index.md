---
title: "Метод System::Xml::XPath::XPathNavigator::GetNamespacesInScope"
linktitle: "GetNamespacesInScope"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::GetNamespacesInScope. Возвращает области имён, действующие в текущем узле, в C++."
type: docs
weight: 4000
url: /ru/cpp/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope method


Возвращает пространства имён в области видимости текущего узла.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | XmlNamespaceScope | Значение [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/), указывающее пространства имён для возврата. |

### ReturnValue

Коллекция IDictionary имён пространств имён, ключами которой являются префиксы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
