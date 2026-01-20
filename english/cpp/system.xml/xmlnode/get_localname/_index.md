---
title: System::Xml::XmlNode::get_LocalName method
linktitle: get_LocalName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode::get_LocalName method. Returns the local name of the node, when overridden in a derived class in C++.'
type: docs
weight: 1400
url: /cpp/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName method


Returns the local name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### ReturnValue

The name of the node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlNode::get_NodeType](../get_nodetype/) of the node: |||
|-|-|
|Type |Name |
|Attribute|The local name of the attribute. |
|CDATA |#cdata-section |
|Comment |#comment |
|Document |#document |
|DocumentFragment |#document-fragment |
|DocumentType |The document type name. |
|Element |The local name of the element. |
|Entity |The name of the entity. |
|EntityReference |The name of the entity referenced. |
|Notation |The notation name. |
|ProcessingInstruction |The target of the processing instruction. |
|Text|#text |
|Whitespace |#whitespace |
|SignificantWhitespace |#significant-whitespace |
|XmlDeclaration|#xml-declaration |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
