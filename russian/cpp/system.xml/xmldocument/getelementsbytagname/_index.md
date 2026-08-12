---
title: "System::Xml::XmlDocument::GetElementsByTagName метод"
linktitle: "GetElementsByTagName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocument::GetElementsByTagName метод. Возвращает XmlNodeList, содержащий список всех дочерних элементов, соответствующих указанным XmlDocument::get_LocalName и XmlNode::get_NamespaceURI, в C++."
type: docs
weight: 3200
url: /ru/cpp/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String, String) method


Возвращает [XmlNodeList](../../xmlnodelist/), содержащий список всех дочерних элементов, соответствующих указанным [XmlDocument::get_LocalName](../get_localname/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | LocalName для сопоставления. Специальное значение **\"*\"** соответствует всем тегам. |
| namespaceURI | String | NamespaceURI для сопоставления. |

### ReturnValue

Список [XmlNodeList](../../xmlnodelist/) содержащий перечень всех совпадающих узлов. Если ни один узел не соответствует указанным **localName** и **namespaceURI**, возвращаемая коллекция будет пустой.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::GetElementsByTagName(String) method


Возвращает [XmlNodeList](../../xmlnodelist/) содержащий список всех дочерних элементов, соответствующих указанному имени.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Квалифицированное имя для сопоставления. Оно сравнивается со значением **get_Name** совпадающего узла. Специальное значение **\"*\"** соответствует всем тегам. |

### ReturnValue

Список [XmlNodeList](../../xmlnodelist/) содержащий перечень всех совпадающих узлов. Если ни один узел не соответствует **name**, возвращаемая коллекция будет пустой.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
