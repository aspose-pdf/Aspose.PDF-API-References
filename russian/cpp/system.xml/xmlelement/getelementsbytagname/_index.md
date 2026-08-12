---
title: "метод System::Xml::XmlElement::GetElementsByTagName"
linktitle: "GetElementsByTagName"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод System::Xml::XmlElement::GetElementsByTagName. Возвращает XmlNodeList, содержащий список всех дочерних элементов, которые соответствуют указанным значениям XmlElement::get_LocalName и XmlElement::get_NamespaceURI в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String, String) method


Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, которые соответствуют указанным значениям [XmlElement::get_LocalName](../get_localname/) и [XmlElement::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя для сопоставления. Символ звездочки (*) является специальным значением, которое соответствует всем тегам. |
| namespaceURI | String | URI пространства имён для сопоставления. |

### ReturnValue

Объект [XmlNodeList](../../xmlnodelist/) содержит список всех совпадающих узлов. Список пуст, если совпадающих узлов нет.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetElementsByTagName(String) method


Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, которые соответствуют указанному [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Тег имени для сопоставления. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. Символ звездочки (*) является специальным значением, которое соответствует всем тегам. |

### ReturnValue

Объект [XmlNodeList](../../xmlnodelist/) содержит список всех совпадающих узлов. Список пуст, если совпадающих узлов нет.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
