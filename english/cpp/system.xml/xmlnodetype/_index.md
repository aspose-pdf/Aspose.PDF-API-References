---
title: System::Xml::XmlNodeType enum
linktitle: XmlNodeType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeType enum. Specifies the type of node in C++.'
type: docs
weight: 6200
url: /cpp/system.xml/xmlnodetype/
---
## XmlNodeType enum


Specifies the type of node.

```cpp
enum class XmlNodeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | This is returned by the [XmlReader](../xmlreader/) if a **Read** method has not been called. |
| Element | 1 | An element (for example, **<item>**). |
| Attribute | 2 | An attribute (for example, **id='123'**). |
| Text | 3 | The text content of a node. A [XmlNodeType::Text](./) node cannot have any child nodes. It can appear as the child node of the [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./), and [XmlNodeType::EntityReference](./) nodes. |
| CDATA | 4 | A CDATA section (for example, **my escaped text**). |
| EntityReference | 5 | A reference to an entity (for example, **&num;**). |
| Entity | 6 | An entity declaration (for example, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | A processing instruction (for example, **<?pi test?>**). |
| Comment | 8 | A comment (for example, ****). |
| Document | 9 | A document object that, as the root of the document tree, provides access to the entire XML document. |
| DocumentType | 10 | The document type declaration, indicated by the following tag (for example, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | A document fragment. |
| Notation | 12 | A notation in the document type declaration (for example, **<!NOTATION...>**). |
| Whitespace | 13 | White space between markup. |
| SignificantWhitespace | 14 | White space between markup in a mixed content model or white space within the **xml:space="preserve"** scope. |
| EndElement | 15 | An end element tag (for example, ****). |
| EndEntity | 16 | Returned when [XmlReader](../xmlreader/) gets to the end of the entity replacement as a result of a call to [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | The XML declaration (for example, **<?xml version='1.0'?>**). The [XmlNodeType::XmlDeclaration](./) node must be the first node in the document. It cannot have children. It is a child of the [XmlNodeType::Document](./) node. It can have attributes that provide version and encoding information. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
