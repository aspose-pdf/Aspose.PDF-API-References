---
title: "System::Xml::XmlNode::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNode::idx_get метод. Возвращает первый дочерний элемент с указанными значениями XmlNode::get_LocalName и XmlNode::get_NamespaceURI в C++."
type: docs
weight: 3000
url: /ru/cpp/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String, String) method


Возвращает первый дочерний элемент с указанными значениями [XmlNode::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | String | Локальное имя элемента. |
| ns | String | URI пространства имен элемента. |

### ReturnValue

Первый [XmlElement](../../xmlelement/) с совпадающими **localname** и **ns**. Возвращает **nullptr**, если совпадения нет.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::idx_get(String) method


Возвращает первый дочерний элемент с указанным [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Полное имя элемента для получения. |

### ReturnValue

Первый [XmlElement](../../xmlelement/), соответствующий указанному имени. Возвращает **nullptr**, если совпадения нет.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
