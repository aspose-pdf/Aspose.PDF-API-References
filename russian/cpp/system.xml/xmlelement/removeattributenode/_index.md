---
title: "System::Xml::XmlElement::RemoveAttributeNode метод"
linktitle: "RemoveAttributeNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlElement::RemoveAttributeNode метод. Удаляет указанный XmlAttribute в C++."
type: docs
weight: 2100
url: /ru/cpp/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Удаляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| oldAttr | SharedPtr\<XmlAttribute\> | Узел [XmlAttribute](../../xmlattribute/), который следует удалить. Если удаленный атрибут имеет значение по умолчанию, оно сразу заменяется. |

### ReturnValue

Удаленный [XmlAttribute](../../xmlattribute/) или **nullptr**, если **oldAttr** не является узлом-атрибутом [XmlElement](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::RemoveAttributeNode(String, String) method


Удаляет [XmlAttribute](../../xmlattribute/), указанный локальным именем и URI пространства имен. (Если удаленный атрибут имеет значение по умолчанию, оно сразу заменяется).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Удаленный [XmlAttribute](../../xmlattribute/) или **nullptr**, если у [XmlElement](../) нет соответствующего узла атрибута.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
