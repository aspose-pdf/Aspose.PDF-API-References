---
title: "Метод System::Xml::XmlReader::ReadToDescendant"
linktitle: "ReadToDescendant"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XmlReader::ReadToDescendant. Перемещает XmlReader к следующему дочернему элементу с указанным локальным именем и пространством имён в C++."
type: docs
weight: 7100
url: /ru/cpp/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String, String) method


Перемещает [XmlReader](../) к следующему дочернему элементу с указанным локальным именем и пространством имён.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента, к которому вы хотите перейти. |
| namespaceURI | String | URI пространства имён элемента, к которому вы хотите перейти. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String,String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToDescendant(String) method


Перемещает [XmlReader](../) к следующему дочернему элементу с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Квалифицированное имя элемента, к которому вы хотите перейти. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
