---
title: "System::Xml::XmlNamedNodeMap::RemoveNamedItem метод"
linktitle: "RemoveNamedItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNamedNodeMap::RemoveNamedItem метод. Удаляет узел с совпадающими значениями XmlNode::get_LocalName и XmlNode::get_NamespaceURI в C++."
type: docs
weight: 900
url: /ru/cpp/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String, String) method


Удаляет узел с совпадающими значениями [XmlNode::get_LocalName](../../xmlnode/get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя удаляемого узла. |
| namespaceURI | String | URI пространства имён удаляемого узла. |

### ReturnValue

Удалённый [XmlNode](../../xmlnode/) или **nullptr**, если совпадающий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::RemoveNamedItem(String) method


Удаляет узел из [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Полное имя удаляемого узла. Имя сравнивается со значением [XmlNode::get_Name](../../xmlnode/get_name/) совпадающего узла. |

### ReturnValue

Удалённый [XmlNode](../../xmlnode/) из этого [XmlNamedNodeMap](../) или **nullptr**, если совпадающий узел не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
