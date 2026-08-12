---
title: "System::Xml::XmlAttributeCollection::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlAttributeCollection::idx_get method. Возвращает атрибут с указанным локальным именем и Uniform Resource Identifier (URI) пространства имён в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(const String\&, const String\&) method


Возвращает атрибут с указанным локальным именем и пространством имён Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя атрибута. |
| namespaceURI | const String\& | URI пространства имен атрибута. |

### ReturnValue

Атрибут с указанным локальным именем и URI пространства имён. Если атрибут не существует, этот метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(const String\&) method


Возвращает атрибут с указанным именем.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const String\& | Полное имя атрибута. |

### ReturnValue

Атрибут с указанным именем. Если атрибут не существует, этот метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(int32_t) method


Возвращает атрибут с указанным индексом.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int32_t | Индекс атрибута. |

### ReturnValue

Атрибут по указанному индексу.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
