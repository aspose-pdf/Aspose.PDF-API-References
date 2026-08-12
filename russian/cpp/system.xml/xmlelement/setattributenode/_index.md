---
title: "System::Xml::XmlElement::SetAttributeNode метод"
linktitle: "SetAttributeNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlElement::SetAttributeNode метод. Добавляет указанный XmlAttribute в C++."
type: docs
weight: 2700
url: /ru/cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Добавляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| newAttr | SharedPtr\<XmlAttribute\> | [XmlAttribute](../../xmlattribute/) узел, который следует добавить в коллекцию атрибутов этого элемента. |

### ReturnValue

Если атрибут заменяет существующий атрибут с тем же именем, возвращается старый [XmlAttribute](../../xmlattribute/); в противном случае возвращается **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::SetAttributeNode(String, String) method


Добавляет указанный [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Указываемый [XmlAttribute](../../xmlattribute/) для добавления.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
