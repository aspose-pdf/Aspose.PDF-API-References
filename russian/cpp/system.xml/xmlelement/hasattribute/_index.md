---
title: "System::Xml::XmlElement::HasAttribute метод"
linktitle: "HasAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlElement::HasAttribute метод. Определяет, имеет ли текущий узел атрибут с указанным локальным именем и URI пространства имён в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String, String) method


Определяет, имеет ли текущий узел атрибут с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя атрибута, который нужно найти. |
| namespaceURI | String | URI пространства имён атрибута, который нужно найти. |

### ReturnValue

**true** if the current node has the specified attribute; otherwise, **false**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::HasAttribute(String) method


Определяет, имеет ли текущий узел атрибут с указанным именем.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя атрибута, который нужно найти. Это квалифицированное имя. Оно сравнивается со значением **get_Name** соответствующего узла. |

### ReturnValue

**true** if the current node has the specified attribute; otherwise, **false**.

## См. также

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
