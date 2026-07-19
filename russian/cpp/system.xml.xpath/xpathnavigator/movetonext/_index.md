---
title: "Метод System::Xml::XPath::XPathNavigator::MoveToNext"
linktitle: "MoveToNext"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::MoveToNext. При переопределении в производном классе перемещает XPathNavigator к следующему узлу‑соседу текущего узла на C++."
type: docs
weight: 6000
url: /ru/cpp/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() method


При переопределении в производном классе перемещает [XPathNavigator](../) к следующему узлу‑соседу текущего узла.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToNext(String, String) method


Перемещает [XPathNavigator](../) к следующему узлу‑соседу с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя следующего узла‑соседа, к которому нужно переместиться. |
| namespaceURI | String | The URI пространства имён следующего узла‑соседа, к которому нужно перейти. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; **false** if there are no more siblings, or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToNext(XPathNodeType) method


Перемещает [XPathNavigator](../) к следующему узлу‑соседу текущего узла, который соответствует указанному [XPathNodeType](../../xpathnodetype/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | XPathNodeType | [XPathNodeType](../../xpathnodetype/) узла‑соседа, к которому нужно перейти. |

### ReturnValue

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise, **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
