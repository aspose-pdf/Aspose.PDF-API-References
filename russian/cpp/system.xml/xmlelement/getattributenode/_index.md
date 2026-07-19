---
title: "System::Xml::XmlElement::GetAttributeNode метод"
linktitle: "GetAttributeNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlElement::GetAttributeNode метод. Возвращает XmlAttribute с указанным локальным именем и URI пространства имён в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String, String) method


Возвращает [XmlAttribute](../../xmlattribute/) с указанным локальным именем и URI пространства имён.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута. |
| namespaceURI | String | URI пространства имен атрибута. |

### ReturnValue

Указанный [XmlAttribute](../../xmlattribute/) или **nullptr**, если соответствующий атрибут не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetAttributeNode(String) method


Возвращает [XmlAttribute](../../xmlattribute/) с указанным именем.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя атрибута, который нужно получить. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. |

### ReturnValue

Указанный [XmlAttribute](../../xmlattribute/) или **nullptr**, если соответствующий атрибут не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
