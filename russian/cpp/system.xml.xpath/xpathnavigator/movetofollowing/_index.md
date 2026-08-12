---
title: "System::Xml::XPath::XPathNavigator::MoveToFollowing метод"
linktitle: "MoveToFollowing"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XPath::XPathNavigator::MoveToFollowing метод. Перемещает XPathNavigator к элементу с указанным локальным именем и URI пространства имён в порядке следования в документе в C++."
type: docs
weight: 5700
url: /ru/cpp/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) method


Перемещает [XPathNavigator](../) к элементу с указанным локальным именем и URI пространства имён в порядке следования в документе.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента. |
| namespaceURI | String | URI пространства имен элемента. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## См. также

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) method


Перемещает [XPathNavigator](../) к элементу с указанным локальным именем и URI пространства имён, к указанной границе, в порядке следования в документе.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента. |
| namespaceURI | String | URI пространства имен элемента. |
| end | SharedPtr\<XPathNavigator\> | Объект [XPathNavigator](../), расположенный на границе элемента, которую текущий [XPathNavigator](../) не перейдёт при поиске следующего элемента. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType) method


Перемещает [XPathNavigator](../) к следующему элементу указанного [XPathNodeType](../../xpathnodetype/) в порядке следования в документе.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | XPathNodeType | [XPathNodeType](../../xpathnodetype/) элемента. [XPathNodeType](../../xpathnodetype/) не может быть [XPathNodeType::Attribute](../../xpathnodetype/) или [XPathNodeType::Namespace](../../xpathnodetype/). |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) method


Перемещает [XPathNavigator](../) к следующему элементу указанного [XPathNodeType](../../xpathnodetype/), к указанной границе, в порядке следования в документе.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | XPathNodeType | [XPathNodeType](../../xpathnodetype/) элемента. [XPathNodeType](../../xpathnodetype/) не может быть [XPathNodeType::Attribute](../../xpathnodetype/) или [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | SharedPtr\<XPathNavigator\> | Объект [XPathNavigator](../), расположенный на границе элемента, которую текущий [XPathNavigator](../) не перейдёт при поиске следующего элемента. |

### ReturnValue

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## См. также

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
