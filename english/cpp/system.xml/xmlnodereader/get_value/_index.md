---
title: System::Xml::XmlNodeReader::get_Value method
linktitle: get_Value
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::get_Value method. Returns the text value of the current node in C++.'
type: docs
weight: 2100
url: /cpp/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value method


Returns the text value of the current node.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### ReturnValue

The value returned depends on the [XmlNodeReader::get_NodeType](../get_nodetype/) of the node.
## Remarks



The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). |||
|-|-|
|Node Type |Value |
|Attribute|The value of the attribute. |
|CDATA|The content of the CDATA section. |
|Comment|The content of the comment. |
|DocumentType|The internal subset. |
|ProcessingInstruction|The entire content, excluding the target. |
|SignificantWhitespace|The white space between markup in a mixed content model. |
|Text|The content of the text node. |
|Whitespace|The white space between markup. |
|XmlDeclaration|The content of the declaration. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
