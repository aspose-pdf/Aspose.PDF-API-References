---
title: "System::Xml::XPath::XPathNavigator::SelectDescendants метод"
linktitle: "SelectDescendants"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::SelectDescendants метод. Выбирает все дочерние узлы текущего узла с указанными локальным именем и URI пространства имён в C++."
type: docs
weight: 7400
url: /ru/cpp/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(String, String, bool) method


Выбирает все потомковые узлы текущего узла с указанным локальным именем и URI пространства имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Локальное имя дочерних узлов. |
| namespaceURI | String | URI пространства имён дочерних узлов. |
| matchSelf | bool | **true** для включения контекстного узла в выборку; иначе **false**. |

### ReturnValue

Объект [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Выбирает все дочерние узлы текущего узла, имеющие соответствующий [XPathNodeType](../../xpathnodetype/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | XPathNodeType | Тип [XPathNodeType](../../xpathnodetype/) дочерних узлов. |
| matchSelf | bool | **true** для включения контекстного узла в выборку; иначе **false**. |

### ReturnValue

Объект [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
