---
title: "System::Xml::XPath::XPathNavigator::SelectChildren метод"
linktitle: "SelectChildren"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::SelectChildren метод. Выбирает все дочерние узлы текущего узла, имеющие указанное локальное имя и URI пространства имен, в C++."
type: docs
weight: 7300
url: /ru/cpp/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(String, String) method


Выбирает все дочерние узлы текущего узла, которые имеют указанное локальное имя и URI пространства имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Локальное имя дочерних узлов. |
| namespaceURI | String | URI пространства имен дочерних узлов. |

### ReturnValue

Объект [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectChildren(XPathNodeType) method


Выбирает все дочерние узлы текущего узла, соответствующие [XPathNodeType](../../xpathnodetype/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | XPathNodeType | Тип [XPathNodeType](../../xpathnodetype/) дочерних узлов. |

### ReturnValue

Объект [XPathNodeIterator](../../xpathnodeiterator/), содержащий выбранные узлы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
