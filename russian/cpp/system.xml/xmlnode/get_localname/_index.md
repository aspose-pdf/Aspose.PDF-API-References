---
title: "System::Xml::XmlNode::get_LocalName метод"
linktitle: "get_LocalName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNode::get_LocalName метод. Возвращает локальное имя узла, когда переопределяется в производном классе в C++."
type: docs
weight: 1400
url: /ru/cpp/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName method


Возвращает локальное имя узла, когда переопределено в производном классе.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### ReturnValue

Имя узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**.
## Примечания



Возвращаемое имя зависит от [XmlNode::get_NodeType](../get_nodetype/) узла: |||
|-|-|
| Тип | Имя |
| Атрибут | Локальное имя атрибута. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Имя типа документа. |
| Элемент | Локальное имя элемента. |
| Entity | Имя сущности. |
| EntityReference | Имя ссылки на сущность. |
| Notation | Имя нотации. |
| ProcessingInstruction | Цель инструкции обработки. |
| Text | #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| XmlDeclaration | #xml-declaration |

## См. также

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
