---
title: "System::Xml::XmlReader::MoveToContent метод"
linktitle: "MoveToContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::MoveToContent метод. Проверяет, является ли текущий узел контентным (текст без пробелов, CDATA, Element, EndElement, EntityReference или EndEntity). Если узел не является контентным, читатель переходит к следующему контентному узлу или к концу файла. Он пропускает узлы следующих типов: ProcessingInstruction, DocumentType, Comment, Whitespace или SignificantWhitespace в C++."
type: docs
weight: 3300
url: /ru/cpp/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent method


Проверяет, является ли текущий узел содержимым (текст без пробельных символов, **CDATA**, **Element**, **EndElement**, **EntityReference** или **EndEntity**) узлом. Если узел не является узлом содержимого, читатель пропускает его до следующего узла содержимого или до конца файла. Он пропускает узлы следующих типов: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** или **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### ReturnValue

Значение [XmlReader::get_NodeType](../get_nodetype/) текущего узла, найденного методом, или [XmlNodeType::None](../../xmlnodetype/), если читатель достиг конца входного потока.

## См. также

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
