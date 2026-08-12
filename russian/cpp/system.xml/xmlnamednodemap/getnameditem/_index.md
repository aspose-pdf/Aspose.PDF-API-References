---
title: "System::Xml::XmlNamedNodeMap::GetNamedItem метод"
linktitle: "GetNamedItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamedNodeMap::GetNamedItem метод. Получает узел с совпадающими значениями XmlNode::get_LocalName и XmlNode::get_NamespaceURI в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String, String) method


Получает узел с совпадающими значениями [XmlNode::get_LocalName](../../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя узла для получения. |
| namespaceURI | String | URI (Uniform Resource Identifier) пространства имён узла для получения. |

### ReturnValue

Объект [XmlNode](../../xmlnode/) с совпадающим локальным именем и URI пространства имён или **nullptr**, если соответствующий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::GetNamedItem(String) method


Получает [XmlNode](../../xmlnode/) по указанному имени.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Полное имя узла для получения. Оно сравнивается со значением [XmlNode::get_Name](../../xmlnode/get_name/) соответствующего узла. |

### ReturnValue

Объект [XmlNode](../../xmlnode/) с указанным именем или **nullptr**, если соответствующий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
