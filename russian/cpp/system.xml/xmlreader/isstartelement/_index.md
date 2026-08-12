---
title: "System::Xml::XmlReader::IsStartElement метод"
linktitle: "IsStartElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::IsStartElement метод. Вызывает XmlReader::MoveToContent и проверяет, является ли текущий узел содержимого стартовым тегом или пустым элементом в C++."
type: docs
weight: 3000
url: /ru/cpp/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method


Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или пустым элементом.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### ReturnValue

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## См. также

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String, String) method


Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или пустым элементом, а также совпадают ли значения [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) найденного элемента с заданными строками.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | String | Строка для сравнения со значением **LocalName** найденного элемента. |
| ns | String | Строка для сравнения со значением **NamespaceURI** найденного элемента. |

### ReturnValue

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String) method


Вызывает [XmlReader::MoveToContent](../movetocontent/) и проверяет, является ли текущий узел содержимого стартовым тегом или пустым элементом, а также совпадает ли значение [XmlReader::get_Name](../get_name/) найденного элемента с заданным аргументом.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Строка, сравниваемая со значением **Name** найденного элемента. |

### ReturnValue

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
