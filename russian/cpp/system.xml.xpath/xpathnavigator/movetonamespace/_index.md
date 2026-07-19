---
title: "System::Xml::XPath::XPathNavigator::MoveToNamespace метод"
linktitle: "MoveToNamespace"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::MoveToNamespace метод. Перемещает XPathNavigator к узлу пространства имён с указанным префиксом пространства имён в C++."
type: docs
weight: 5900
url: /ru/cpp/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace method


Перемещает [XPathNavigator](../) к узлу пространства имён с указанным префиксом пространства имён.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Префикс пространства имён узла. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the specified namespace; **false** if a matching namespace node was not found, or if the [XPathNavigator](../) is not positioned on an element node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
