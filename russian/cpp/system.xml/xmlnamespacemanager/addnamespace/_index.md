---
title: "System::Xml::XmlNamespaceManager::AddNamespace метод"
linktitle: "AddNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamespaceManager::AddNamespace метод. Добавляет указанное пространство имён в коллекцию в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace method


Добавляет указанное пространство имён в коллекцию.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс, который следует связать с добавляемым пространством имён. Используйте [String::Empty](../../../system/string/empty/) для добавления пространства имён по умолчанию. Если [XmlNamespaceManager](../) будет использоваться для разрешения пространств имён в выражении XML Path Language ([XPath](../../../system.xml.xpath/)), необходимо указать префикс. Если в выражении [XPath](../../../system.xml.xpath/) префикс не указан, считается, что Uniform Resource Identifier (URI) пространства имён является пустым пространством имён. Для получения дополнительной информации о выражениях [XPath](../../../system.xml.xpath/) и [XmlNamespaceManager](../) см. методы XmlNode::SelectNodes(String) и XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) методы. |
| uri | String | Пространство имён для добавления. |

## См. также

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
