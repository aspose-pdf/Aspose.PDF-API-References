---
title: "System::Xml::XPath::XPathNavigator::MoveToAttribute метод"
linktitle: "MoveToAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::MoveToAttribute метод. Перемещает XPathNavigator к атрибуту с соответствующим локальным именем и URI пространства имён в C++."
type: docs
weight: 5100
url: /ru/cpp/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute method


Перемещает [XPathNavigator](../) к атрибуту с соответствующим локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имён атрибута; **nullptr** для пустого пространства имён. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the attribute; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
