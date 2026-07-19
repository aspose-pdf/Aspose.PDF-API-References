---
title: "System::Xml::XmlReader::ReadToNextSibling метод"
linktitle: "ReadToNextSibling"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadToNextSibling метод. Перемещает XmlReader к следующему элементу‑соседу с указанным локальным именем и URI пространства имён в C++."
type: docs
weight: 7300
url: /ru/cpp/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String, String) method


Перемещает [XmlReader](../) к следующему элементу‑соседу с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Локальное имя элемента‑соседа, к которому вы хотите перейти. |
| namespaceURI | String | URI пространства имён элемента‑соседа, к которому вы хотите перейти. |

### ReturnValue

**true** if a matching sibling element is found; otherwise, **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToNextSibling(String) method


Перемещает [XmlReader](../) к следующему элементу‑соседу с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Квалифицированное имя элемента‑соседа, к которому вы хотите перейти. |

### ReturnValue

**true** if a matching sibling element is found; otherwise **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## См. также

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
